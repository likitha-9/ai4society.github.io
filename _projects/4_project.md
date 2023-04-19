---
title: "Insights with Power Data"
team: "Bharath Muppasani, Cheyyur Jaya Anand, Chinmayi Appajigowda, Lokesh Johri, Biplav Srivastava"
description: "The project aims to identify power usage patterns of any system, like buildings or factories, of interest using the harmonics data obtained from MiDAS IoT sensor. We also make power usage dataset (electricity consumption data and harmonics data) available from 8 institutions in manufacturing, education and medical institutions from the US and India - [More Details](https://ai4society.github.io/power_page/)"  
Relevant_Papers: "[2022-1](../papers#2022-1), [2023-1](../papers#2023-1), [2022-4](../papers#2022-4)"
# more_details: "[here](https://sites.google.com/site/biplavsrivastava/research-1/fast-slow-planning)"
---


<script>
function showItem(index) {
	var list = document.getElementById("publications");
	var item = list.getElementsByTagName("li")[index];
	item.style.display = "block";
}
function filterPublications() {
        var input, filter, ul, li, a, i;
        input = document.getElementById('search');
        filter = input.value.toUpperCase();
        ul = document.getElementById("publications");
        li = ul.getElementsByTagName('li');
        for (i = 0; i < li.length; i++) {
          a = li[i].getElementsByTagName("a")[0];
          if (a.innerHTML.toUpperCase().indexOf(filter) > -1) {
            li[i].style.display = "";
          } else {
            li[i].style.display = "none";
          }
        }
      }
</script>