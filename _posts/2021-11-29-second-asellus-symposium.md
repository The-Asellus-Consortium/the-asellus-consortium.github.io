---
layout: post
title: The 2nd Asellus symposium
excerpt: "On November 26th the 2nd Asellus Symposium was held online. The symposium synopsis and all recorded talks are available here."
---

<script src="/assets/js/jquery.min.js"></script>
<script src="/assets/js/jquery.fitvids.js"></script>

<script>
$(document).ready(function(){
$("video-item").fitVids();
$("body").fitVids();
});
</script>

On November 26th 2021, the 2nd Asellus Symposium was held online. There were some 40+ registered participants from institutions in 14 countries. Below you can find the final program, links to all recorded talks on youtube (unlisted) and a summary of the discussion notes.

It was great to see the broad range of topics that were covered in presentations and during the discussion sessions (see synthesis of insight below) - from selective forces and determinants of pigmentation, intraspecific variation in innovativeness and behavioural responses to predator cues, foraging ecology and life-history variation, and species interactions (host-parasite, host-microbiome, predator-prey) to phylogeography and microevolution, along the surface-waterpipe-cave continuum, as well as natural and human-impacted environments. 

The broad range of methods that are already being used - different phenotyping methods (microscopy, computer vision techniques for image and video analyses [e.g. https://www.phenopype.org], microbiomics and metabolomics), genomics (several draft genomes have been attempted/are in preparation), lab rearing and maintenance, and long-term data acquisition - that can be shared across the community set the stage for highly integrative studies. 

This clearly shows that *Asellus aquaticus* is ready to fledge as a model system for eco-evo-devo studies both for basic and applied questions. At the same time, several knowledge gaps were identified and for a very short non-exhaustive summary, these include poor understanding of basic requirements of *A. aquaticus* (e.g. in lab rearing), lack of a well-annotated genome, and limited knowledge on sexual selection and phenology.

# Documents

<p>Symposium program: <a href="/assets/files/AsellusSymposium21_programm.pdf" download><button> Download </button></a></p>
<p>Scientific synopsis and notes: <a href="/assets/files/AsellusSymposium21_Synthesis18Dec21.pdf" download> <button> Download</button> </a></p>



<p>yaml file: <a href="https://raw.githubusercontent.com/phenopype/phenopype-templates/main/templates/detection/single1.yaml" download="https://raw.githubusercontent.com/phenopype/phenopype-templates/main/templates/detection/single1.yaml"><button> Download </button></a></p>

<a id="link" href="https://raw.githubusercontent.com/phenopype/phenopype-templates/main/templates/detection/single1.yaml">
		Download this file
</a>
	
<script>
 function download_file(filelink) {
	 
	 	var parts = filelink.split('/');
		var filename = parts.pop() || parts.pop();  // handle potential trailing slash
	 
     var req = new XMLHttpRequest();
     req.open("GET", filelink, true);
     req.responseType = "blob";
     req.onload = function (event) {
         var blob = req.response;
         var fileName = req.getResponseHeader("fileName") //if you have the fileName header available
         var link=document.createElement('a');
         link.href=window.URL.createObjectURL(blob);
         link.download=filename;
         link.click();
     };

     req.send();
 }
</script>

 <script> 
		var buttonName = "sd-sphinx-override sd-btn sd-text-wrap sd-btn-primary reference external"
		var url1 = "https://raw.githubusercontent.com/phenopype/phenopype-templates/main/templates/detection/single1.yaml";
		document.write('<a class="buttonName" type="button" onclick="download_file(url1)">Download</a>');
 </script>
			 

# Recorded talks

<div class="demo-container">

	<div class="demo-item" style="background-color: rgb(255,229,153)">
		<div>
			<p>Keynote (40 mins)</p>
		</div>
	</div>
	
	<div class="demo-item" style="background-color: rgb(200,200,200)">
		<div>
			<p>Regular talk (12 mins)</p>
		</div>
	</div>
	
	<div class="demo-item" style="background-color: rgb(159,197,232)">
		<div>
			<p>Flash talk (3 mins)</p>
		</div>
	</div>
	
	</div>

## Keynote presentation

<div class="video-container">
	<div class="video-item" style="background-color:rgb(255,229,153);" >
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/TgG-AR9n2YM?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Meredith Protas</h5>
		<p>The genetic basis of pigmentation differences in multiple populations of Asellus aquaticus</p>
	</div>
</div>


## Session 1

<div class="video-container">

	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/uAcXtB_ayRY?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Lidia Sworobowicz</h5>
		<p>Phylogeography of <i>Asellus aquaticus</i> in Europe</p>
	</div>
		
	<div class="video-item" style="background-color:rgb(159,197,232)">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/zWt9rfb5zm0?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>		
		<h5>Tristan Lefebure</h5>
		<p>The Asellidae ecological genomic model</p>
	</div>
	
</div>

## Session 2

<div class="video-container">

	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/NGfA5yYkwHo?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Vid Bakovic & Dominic Wright</h5>
		<p><i>Asellus aquaticus</i> cave and lake ecotypes on the island of Gotland, Sweden</p>
	</div>

	
	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/f4blZUzPU10?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>	
		<h5>Anna Biro</h5>
		<p>Morphological comparison of surface vs cave <i>Asellus aquaticus</i> populations</p>
	</div>
	
	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/mc8GsX8_L7s?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Žiga Fišer</h5>
		<p>Comparative phenology of cave and surface populations of <i>Asellus aquaticus</i></p>
	</div>

	<div class="video-item" style="background-color:rgb(159,197,232)">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/kNXrQEow4kk?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Moritz Lürig</h5>
		<p>Phenotypic variation of <i>Asellus hilgendorfi</i> on Hokkaido (Japan)</p>
	</div>
	
</div>

## Session 3

<div class="video-container">

	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/QwI6c2CK5Gk?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>	
		<h5>Emmanuelle Prest</h5>
		<p>Asellus in drinking water distribution systems</p>
	</div>
	
	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/8oRu5o1SqKM?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Gábor Herczeg</h5>
		<p>Food preference and food type innovation in surface- vs. cave-dwelling <i>Asellus aquaticus</i></p>
	</div>
	
	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/ZrXp6dusa5I?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Sára Sztruhala</h5>
		<p>Population divergence in aggregation and sheltering behaviour in surface and cave-adapted <i>Asellus aquaticus</i></p>
	</div>

	<div class="video-item" style="background-color:rgb(159,197,232)">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/xx-ruBl-zGw?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Claudia Tugui</h5>
		<p>Towards understanding the co-occurrence of Asellus and Aeromonas in Dutch drinking water distribution systems</p>
	</div>
	
</div>


## Session 4

<div class="video-container">
	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/3LXT8GE9boI?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Simona Kralj Fišer</h5>
		<p>Behavioural variation at different hierarchical levels during adaptation from fluctuating to stable environments</p>
	</div>
	
	<div class="video-item">
		Video missing - will be uploaded soon!
		<h5>Hajriz Berisha</h5>
		<p>Behavioural/Increased movement activity of the <i>Asellus aquaticus</i> in a food abundant, predator-free cave habitat</p>
	</div>
	
	<div class="video-item" style="max-width:calc(99%/2)">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/ZrXp6dusa5I?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Gergely Horvath</h5>
		<p>Divergence in exploratory behaviour between surface and cave-adapted <i>Asellus aquaticus</i></p>
	</div>
</div>


## Session 5

<div class="video-container">

	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/jPjaDiKLwh8?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Elvira Lafuente</h5>
		<p>Coping with anthropogenic stress:the role of gut-associated bacteria in A. aquaticus</p>
	</div>
	
	<div class="video-item">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/FcmZ9-cGL7s?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Grega Benko</h5>
		<p>Acanthocephalan-induced phenotypic alterations of <i>Asellus aquaticus</i></p>
	</div>
	
	<div class="video-item" style="background-color:rgb(159,197,232)">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/kjyjPaTnonQ?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Terezia Horvathova</h5>
		<p>Gut microbiome of freshwater isopods: a new source of antimicrobial compounds?</p>
	</div>

	<div class="video-item" style="background-color:rgb(159,197,232)">
		<iframe width="1280" height="720" src="https://www.youtube.com/embed/Ttip7mYobhw?list=PL5Y_w-GAllxiU3HHpHwA2GwhXA8pvV4jS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		<h5>Christoph Vorburger</h5>
		<p>Potential reproductive manipulators in <i>Asellus aquaticus</i></p>
	</div>
	
</div>

