---
permalink: /Papers/
title: <span style="color:maroon">**Papers**</span>
excerpt: "Papers"
author_profile: true
redirect_from: 
  - /papers/
  - /papers.html
---


<input type="text" id="myInput" onkeyup="filterPublications()" placeholder="Search for publications...">

<ul id="publicationList">
  <li><strong>2022-2</strong> - Marianna Bergamaschi Ganapini, Murray Campbell, Francesco Fabiano, Lior Horesh, Jon Lenchner, Andrea Loreggia, Nicholas Mattei, Taher Rahgooy, Francesca Rossi, Biplav Srivastava, Kristen Brent Venable, Combining Fast and Slow Thinking for Human-like and Efficient Navigation in Constrained Environments. ICLR Nesy. Preprint on Arxiv at:
[https://arxiv.org/abs/2201.07050](https://arxiv.org/abs/2201.07050), 2022 [Neuro-Symbolic AI, Metacognition]</li>

  <li><strong>2022-3</strong> - Why is my System Biased?: Rating of AI Systems through a Causal Lens, AIES 2022 [Student Abstract] - [[PDF](https://dl.acm.org/doi/10.1145/3514094.3539556)]</li>

  <li><strong>2022-4</strong> - Bharath Muppasani, Cheyyur Jaya Anand, Chinmayi Appajigowda, Biplav Srivastava, Lokesh Johri, Power Forecasting and Anomaly Detection with MIDAS IoT-based Sensor, DOI: 10.13140/RG.2.2.17358.33600, 2022 [Power data, machine learning]</li>

  <li><strong>2021-1</strong> - Vishal Pallagani and Biplav Srivastava, Prudent: A Generic Dialog Agent for Information 
Retrieval That Can Flexibly Mix Automated Planning and Reinforcement Learning, International 
Conference on Automated Planning and Scheduling (ICAPS) Demonstration Track, 2021 
[Planning/RL, Dialog]</li>

  <li><strong>2021-2</strong> - Marianna Ganapini, Murray Campbell, Francesco Fabiano, Lior Horesh, Jon Lenchner, Andrea 
Loreggia, Nicholas Mattei, Francesca Rossi, Biplav Srivastava and Kristen Brent Venable, 
Thinking Fast and Slow in AI: the Role of Metacognition, ACAIN 2022, Preprint on Arxiv at: [https://arxiv.org/abs/2110.01834](https://arxiv.org/abs/2110.01834) [Neuro-Symbolic AI, Metacognition]</li>
</ul>

<script>
function filterPublications() {
  var input, filter, ul, li, a, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  ul = document.getElementById("publicationList");
  li = ul.getElementsByTagName("li");
  for (i = 0; i < li.length; i++) {
    a = li[i].getElementsByTagName("strong")[0];
    txtValue = a.textContent || a.innerText;
    if (txtValue.toUpperCase().indexOf(filter) > -1) {
      li[i].style.display = "";
    } else {
      li[i].style.display = "none";
    }
  }
}
</script>




