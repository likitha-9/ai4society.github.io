---
title: "[Insights with Power Data](https://ai4society.github.io/power_page/)"
team: "Bharath Muppasani, Cheyyur Jaya Anand, Chinmayi Appajigowda, Lokesh Johri, Biplav Srivastava"
description: "The project aims to identify power usage patterns of any system, like buildings or factories, of interest using the harmonics data obtained from MiDAS IoT sensor. We also make power usage dataset (electricity consumption data and harmonics data) available from 8 institutions in manufacturing, education and medical institutions from the US and India "  
Relevant_Papers: "[2021-1](../papers#2021-1), [2022-2](../papers#2021-2)"
more_details: "[here](https://sites.google.com/site/biplavsrivastava/research-1/fast-slow-planning)"
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