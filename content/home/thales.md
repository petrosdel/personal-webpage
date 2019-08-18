+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 85  # Order that this section will appear.

title = "Thales and Friends"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++



<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML//EN">
<html>

<head>
<title>Petros Dellaportas</title>
<div id="logo">
  <img src="ucl.png" width=100%; height=7%>
</div>

<link rel="stylesheet" type="text/css" href="PD_desktop.css">
<meta name="keywords" content="Petros Dellaportas, Petros at UCL,Bayesian statistics,MCMC,Bayesian theory and applications, financial modelling, big data, Gibbs sampler, hierarchical models, Bayesian inference">
<meta name="author" content="Petros Dellaportas">
<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0;" /> 
<meta name="HandheldFriendly" content="True" />
</head>



<script>
function show(element) {
    if (typeof(element) != "object")	{
		element = document.getElementById(element);
    }
    
    if (typeof(element) == "object") {
		element.style.display = '';
    }
}


function hide(element) {
    if (typeof(element) != "object")	{
		element = document.getElementById(element);
    }
    
    if (typeof(element) == "object") {
		element.style.display = 'none';
    }
}

function show_content(optionsId) {
	var ids = new Array('home','research','students','editor','grst','thales');
	show(optionsId);
	document.getElementById(optionsId + '_link').className = 'active';

	for (var i = 0; i < ids.length; i++)
	{
	    if (ids[i] == optionsId) continue;
	    hide(ids[i]);
	    document.getElementById(ids[i] + '_link').className = '';
	}
}

function show_research(optionsId) {
	var ids = new Array('all','applications','financial','model','methodology','book','notes');
	show(optionsId);
	document.getElementById(optionsId + '_link').className = 'active';

	for (var i = 0; i < ids.length; i++)
	{
	    if (ids[i] == optionsId) continue;
	    hide(ids[i]);
	    document.getElementById(ids[i] + '_link').className = '';
	}
}

</script>



<!----    Main body     -----------> 
<body>
<h1>
Petros Dellaportas
</h1>

<div id="menu">
	 <a id="home_link" href="#" class="active" 
	onmouseover="show_content('home'); return false;">Home</a> 
	<a id="research_link" href="#"
	onmouseover="show_content('research'); return false;">Research</a>
	 <a id="students_link" href="#" 
	 onmouseover="show_content('students'); return false;">Supervision</a>
	 <a id="editor_link" href="#" 
	onmouseover="show_content('editor');  return false;">Editorial work</a>
	<a id="grst_link" href="#"
	 onmouseover="show_content('grst'); return false;">Greek Stochastics</a> 
	 <a id="thales_link" href="#"
	 onmouseover="show_content('thales'); return false;">Thales+Friends</a> 
</div>

<br><br>



<!----------- Home -------------------------------------->
<div id="home" style="display: block">
	<table>
		<tr>      
		 Petros Dellaportas has a joint appointment as a professor in Statistical Science in the <a  href="https://www.ucl.ac.uk/statistics"> department of Statistical Science</a>, 
		<a  href="http://www.ucl.ac.uk/"> University College London</a> and as a professor of Statistics in the <a  href="https://www.dept.aueb.gr/en/content/%CF%84%CE%BC%CE%AE%CE%BC%CE%B1-%CF%83%CF%84%CE%B1%CF%84%CE%B9%CF%83%CF%84%CE%B9%CE%BA%CE%AE%CF%82-2"> department of Statistics</a>, <a  href="https://www.aueb.gr/en">  Athens University of Economics and Business</a>.         
    		He is also a Turing fellow of the <a  href="https://turing.ac.uk/"> Alan Turing Institute</a>.
		<br>
		<br>
		 <b> Research interests </b>: Bayesian theory and applications, financial modelling, machine learning.                                 
		<br>
		<br>
		 Professor Dellaportas'  <b> Google Scholar</b> profile is <a  href="https://scholar.google.gr/citations?user=E0FmV8AAAAAJ&hl=en"> here</a>.  <br>
		<br> <br>
		</tr>
		
	<table>
	<tr>
	   <td width=20%> 
	   <div id="picture"> <img src="pd_test.jpg"></div> 
	   </td>
	   <td width=5%> </td>
	   <td width=70%>
	   <b> Recent articless:</b><br><br>
	   Hirt M., Dellaportas P and Durmus A. (2019).   <a href="https://arxiv.org/pdf/1904.07153.pdf"> Copula-like variational inference.</a> <br>
       <br>
	   Alexopoulos A., Dellaportas P., Papaspiliopoulos O. (2019)  <a href="https://arxiv.org/pdf/1904.05312.pdf">   Bayesian prediction of jumps in large panels of time series data.</a> <br>
       <br>
       Arakelian, V., Dellaportas P, Savona R. And Vezzoli M (2019)   <a href="https://www.researchgate.net/profile/Veni_Arakelian/publication/326508208_Sovereign_Risk_Zones_in_Europe_During_and_After_the_Debt_Crisis/links/5b51be380f7e9b240ff126e1/Sovereign-Risk-Zones-in-Europe-During-and-After-the-Debt-Crisis.pdf"> 
       Scalable Bayesian Sovereign risk zones in Europe during and after the debt crisis.  To appear in <em> Quantitative Finance </em>.   </a> <br>
       <br>
       Panos, A., Dellaportas P. and Titsias M. (2018)  <a href="https://arxiv.org/abs/1807.02537"> Fully Scalable Gaussian Processes using Subspace Inducing Inputs.</a> <br>
       <br>
		Hirt, M. and Dellaportas P. (2018)  <a href="https://arxiv.org/abs/1805.09406"> Scalable Bayesian Learning for State Space Models using Variational Inference with SMC Samplers. </a>
		To appear in <em> AISTATS 2019</em>.  <br>
		<br>
Alexopoulos A., Dellaportas P. and Forster J.J. (2018)    <a 			href="https://arxiv.org/abs/1805.12257"> Bayesian forecasting of mortality rates using latent Gaussian models.</a> 
 To appear in the <em> Journal of Royal Statistical Society-Series A</em>. 
<br>
		<br>

	   Dellaportas P., Plataniotis A. and Titsias M.   <a 			href="http://arxiv.org/pdf/1510.05257.pdf"> Scalable 			inference for a full multivariate
			stochastic volatility model.</a> <br>
		<br>
Dellaportas, P. and Tsionas MG (2017). <a href="Dellaportas_Tsionas_final.pdf"> Importance sampling from posterior distributions using copula-like
approximations. </a>  To appear in the <em> Journal of Econometrics</em>. 

	   <br> <br>
Finke, Axel, Ruth King, Alexandros Beskos, and Petros Dellaportas.  <a href="https://arxiv.org/abs/1708.04221">"Efficient sequential Monte Carlo algorithms for integrated population models." 
</a> arXiv preprint arXiv:1708.04221 (2017).  To appear in <em> Journal of Agricultural, Biological, and Environmental Statistics</em>.
<br>
		<br>
Owen JL Rackham, Sarah R Langley, Thomas Oates, Eleni Vradi, Nathan Harmston, Prashant K
Srivastava, Jacques Behmoaras, Petros Dellaportas, Leonardo Bottolo, and Enrico Petretto. A
Bayesian Approach for Analysis of Whole-Genome Bisulfite Sequencing Data Identifies DiseaseAssociated
Changes in DNA Methylation (2017).  <em> Genetics </em>  205.4, 1443ñ-1458.</a>
<br>
		<br>
 <br> <b> Last Greek Stochastics conference:</b>
	   <a href="http://www.stochastics.gr/meetings/kappa/index.html"> Greek Stochastics kappa </a>: Statistical learning, Athens, Greece, 19-22 December 2018. 
	   Lectures by Francois Caron, Arthur Gretton and Gergely Neu</li></a> <br>
       
       <br> <b> Next Greek Stochastics conference:</b>
       <a href="http://www.stochastics.gr/meetings/lambda/index.html"> Greek Stochastics lambda </a>: Stochastic processes and computation. Corfu, Greece, 27-19/8/2019.  
       Lectures by Pierre Del Moral, Grigorios Pavliotis and Jonathan Weare</li></a> <br>



		<br>
 <br> <b> Workshop 17-18/6/2019, Barcelona, Spain:</b>
	   <a href="https://www.barcelonagse.eu/summer-forum/workshop-machine-learning-economics"> Machine Learning for Economics </a>.  Co-organised with Stephen Hansen, Omiros Papaspiliopoulos,  Martin Weidner</li></a> <br>
       
 <br> <b> Workshop 20-21/5/2019, Cambridge, UK:</b>
	   <a href="https://www.bigdata.cam.ac.uk/events/advances-and-challenges-machine-learning-languages"> Advances and challenges in Machine LEarning Languages </a>.  Co-organised with Hong Ge, Zoubin Gharamani, Maria Skoularidou</li></a> <br>

 <br> <b> Conference 2-3/9/2019, University of St Andrews, UK:</b>
	   <a href="https://inomics.com/conference/10th-european-seminar-on-bayesian-econometrics-1366617"> 10th European Seminar on Bayesian Econometrics </a>.  Keynote Speaker.</li></a> <br>


       
       <br> 


<br>



<!--   EDW EVALA SXOLIA
<br><<br><br><br><br>
-->   
		</td>
	</tr>
	</table>		

	<table>
	 <tr>
		<td width="25%">
		<br> <br>
		<b>Address for mail: </b><br>
		 Department of Statistical Science,<br>
		 University College ,<br>
		 Gower Street ,<br>
		 London, WC1E 6BT <br>
		<br>
		</td>
		<td width="25%">
		<br> <br>
		<b>Address for visiting: </b> <br>
		 Department of Statistical Science,<br>
		 University College ,<br>
		 1-19 Torrington Place, <br>
		London WC1E 7HB <br>
		<br>
		</td>
		<td width="25%">
		<br> <br>
		<b>Email: </b> <br> 
		 p dot <em> surname </em>  at ucl.ac.uk <br><br>
		 <b>Tel: </b> <br>
		  +44(0)2031083244  <br> <br> 
		</td>
		
		<td width="5%"> 
			<script type="text/javascript">
			var sc_project=10722950; 
			var sc_invisible=1; 
			var sc_security="eb6cea1e"; 
			var scJsHost = (("https:" == document.location.protocol) ?
			"https://secure." : "http://www.");
			document.write("<sc"+"ript type='text/javascript' src='" +
			scJsHost+
			"statcounter.com/counter/counter.js'></"+"script>");
			</script>
			<noscript>
			<div class="statcounter">
			<a title="hit counter"
			href="http://statcounter.com/free-hit-counter/"
			target="_blank"><img class="statcounter"
			src="http://c.statcounter.com/10722950/0/eb6cea1e/1/"
			alt="hit counter"></a>
			</div>
			</noscript>
	</noscript>
		</td>
	</tr>
	</table>
</table>
</div>


<!--------------------Research -------------------------->
  
<div id="research" style="display: none">

	<div id="themes">
		<a id="all_link" href="#" class="active" 
		onmouseover="show_research('all'); return false;">All Articles</a> 
		<br>
		<br>
		
		<a id="applications_link" href="#" 
		onmouseover="show_research('applications'); return false;">Applications</a> 
		<br>
		<br>
		
		<a id="financial_link"href="#" 
		onmouseover="show_research('financial');return false;">Financial Statistics</a>
		<br>
		<br>
		
		<a id="model_link" href="#"  
		onmouseover="show_research('model');return false;">Model determination</a>
		<br>
		<br>
		
		
		<a id="methodology_link" href="#" 
		onmouseover="show_research('methodology'); return false;">Methodology</a>
		<br>
		<br>
		
		<a id="book_link" href="#" 
		onmouseover="show_research('book'); return false;">Book</a>
		<br>
		<br>
		  
		<a id="notes_link" href="#" 
		onmouseover="show_research('notes');return false;">MCMC Notes</a>
	</div>  
  
  	<div id="descr">
	
		<div id="all" style="display: block">

			<table>
			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="bottolo2015">1</a>]
			</td>
			<td class="bibtexitem">
			Leonardo Bottolo and Petros Dellaportas.
			 Bayesian hierarchical mixture models.
			 In <em>Statistical Analysis for High Dimensional Data, Abel Symposia
			  11</em>, 91--103. Springer International Publishing Switzerland, 2016.
			[&nbsp;<a href="PD_citations_bib.html#bottolo2015">bib</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="petralias2015volatility">2</a>]
			</td>
			<td class="bibtexitem">
			Athanassios Petralias and Petros Dellaportas.
			 Volatility prediction based on scheduled macroeconomic announcements.
			 <em>Canadian Journal of Statistics</em>, 43:199-223, 2015.
			[&nbsp;<a href="PD_citations_bib.html#petralias2015volatility">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/cjs.11247/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="rackham2015wgbssuite">3</a>]
			</td>
			<td class="bibtexitem">
			Owen&nbsp;JL Rackham, Petros Dellaportas, Enrico Petretto, and Leonardo Bottolo.
			 Wgbssuite: simulating whole-genome bisulphite sequencing data and
			  benchmarking differential dna methylation analysis tools.
			 <em>Bioinformatics</em>, 31:2371-3, 2015.
			[&nbsp;<a href="PD_citations_bib.html#rackham2015wgbssuite">bib</a>&nbsp;| 
			<a href="http://bioinformatics.oxfordjournals.org/content/early/2015/03/25/bioinformatics.btv114.full.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2014arbitrage">4</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Aleksandar Mijatovic.
			 Arbitrage-free prediction of the implied volatility smile.
			 <em>Risk Magazine</em>, pages 62-67, 2014.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2014arbitrage">bib</a>&nbsp;| 
			<a href="http://www.risk.net/risk-magazine/technical-paper/2342471/smile-transformation-for-price-prediction">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="andersen2014communication">5</a>]
			</td>
			<td class="bibtexitem">
			J&oslash;rgen&nbsp;Vitting Andersen, Ioannis Vrontos, Petros Dellaportas, and Serge
			  Galam.
			 Communication impacting financial markets.
			 <em>EPL (Europhysics Letters)</em>, 108(2):28007, 2014.
			[&nbsp;<a href="PD_citations_bib.html#andersen2014communication">bib</a>&nbsp;| 
			<a href="http://arxiv.org/pdf/1410.2550.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2014museum">6</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Effie Papageorgiou, and Georgios Panagiaris.
			 Museum factors affecting the ageing process of organic materials:
			  review on experimental designs and the invenvorg project as a pilot study.
			 <em>Heritage Science</em>, 2(1):2, 2014.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2014museum">bib</a>&nbsp;| 
			<a href="http://www.biomedcentral.com/content/pdf/2050-7445-2-2.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="damien2013bayesian">7</a>]
			</td>
			<td class="bibtexitem">
			Paul Damien, Petros Dellaportas, Nicholas&nbsp;G Polson, and David&nbsp;A Stephens.
			 <em>Bayesian Theory and Applications</em>.
			 Oxford University Press, 2013.
			[&nbsp;<a href="PD_citations_bib.html#damien2013bayesian">bib</a>&nbsp;| 
			<a href="http://ukcatalogue.oup.com/product/9780199695607.do">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="petralias2013mcmc">8</a>]
			</td>
			<td class="bibtexitem">
			Athanassios Petralias and Petros Dellaportas.
			 An mcmc model search algorithm for regression problems.
			 <em>Journal of Statistical Computation and Simulation</em>,
			  83(9):1722-1740, 2013.
			[&nbsp;<a href="PD_citations_bib.html#petralias2013mcmc">bib</a>&nbsp;| 
			<a href="https://www.tol-project.org/svn/tolp/OfficialTolArchiveNetwork/ArimaTools/doc/bibliografia/MCMC/An%20MCMC%20model%20search%20algorithm%20for.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012cholesky">9</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Mohsen Pourahmadi.
			 Cholesky-garch models with applications to finance.
			 <em>Statistics and Computing</em>, 22(4):849-855, 2012.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2012cholesky">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-011-9251-2">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kateri2012conditional">10</a>]
			</td>
			<td class="bibtexitem">
			Maria Kateri and Petros Dellaportas.
			 Conditional symmetry models for three-way contingency tables.
			 <em>Journal of Statistical Planning and Inference</em>,
			  142(8):2430-2439, 2012.
			[&nbsp;<a href="PD_citations_bib.html#kateri2012conditional">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0378375812000730">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012control">11</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioannis Kontoyiannis.
			 Control variates for estimation based on reversible markov chain
			  monte carlo samplers.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 74(1):133-161, 2012.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2012control">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1467-9868.2011.01000.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="arakelian2012contagion">12</a>]
			</td>
			<td class="bibtexitem">
			Veni Arakelian and Petros Dellaportas.
			 Contagion determination via copula and volatility threshold models.
			 <em>Quantitative Finance</em>, 12(2):295-310, 2012.
			[&nbsp;<a href="PD_citations_bib.html#arakelian2012contagion">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/14697680903410023">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012joint">13</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 Joint specification of model space and parameter space prior
			  distributions.
			 <em>Statistical Science</em>, 27(2):232-246, 2012.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2012joint">bib</a>&nbsp;| 
			<a href="http://arxiv.org/pdf/1207.5651.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="papathomas2011novel">14</a>]
			</td>
			<td class="bibtexitem">
			Michalis Papathomas, Petros Dellaportas, and Vasilis&nbsp;GS Vasdekis.
			 A novel reversible jump algorithm for generalized linear models.
			 <em>Biometrika</em>, 98(1):231-236, 2011.
			[&nbsp;<a href="PD_citations_bib.html#papathomas2011novel">bib</a>&nbsp;| 
			<a href="http://biomet.oxfordjournals.org/content/early/2011/02/06/biomet.asq071.short">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="meligkotsidou2011forecasting">15</a>]
			</td>
			<td class="bibtexitem">
			Loukia Meligkotsidou and Petros Dellaportas.
			 Forecasting with non-homogeneous hidden markov models.
			 <em>Statistics and Computing</em>, 21(3):439-449, 2011.
			[&nbsp;<a href="PD_citations_bib.html#meligkotsidou2011forecasting">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-010-9180-5">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kalogeropoulos2011likelihood">16</a>]
			</td>
			<td class="bibtexitem">
			Konstantinos Kalogeropoulos, Petros Dellaportas, and Gareth&nbsp;O Roberts.
			 Likelihood-based inference for correlated diffusions.
			 <em>Canadian journal of statistics</em>, 39(1):52-72, 2011.
			[&nbsp;<a href="PD_citations_bib.html#kalogeropoulos2011likelihood">bib</a>&nbsp;| 
			<a href="http://economics.ouls.ox.ac.uk/11898/1/chibpittshephard.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kalogeropoulos2010inference">17</a>]
			</td>
			<td class="bibtexitem">
			Konstantinos Kalogeropoulos, Gareth&nbsp;O Roberts, and Petros Dellaportas.
			 Inference for stochastic volatility models using time change
			  transformations.
			 <em>The Annals of Statistics</em>, pages 784-807, 2010.
			[&nbsp;<a href="PD_citations_bib.html#kalogeropoulos2010inference">bib</a>&nbsp;| 
			<a href="http://projecteuclid.org/download/pdfview_1/euclid.aos/1266586614">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="tarantola2008bayesian">18</a>]
			</td>
			<td class="bibtexitem">
			Claudia Tarantola, Guido Consonni, and Petros Dellaportas.
			 Bayesian clustering for row effects models.
			 <em>Journal of Statistical Planning and Inference</em>,
			  138(7):2223-2235, 2008.
			[&nbsp;<a href="PD_citations_bib.html#tarantola2008bayesian">bib</a>&nbsp;| 
			<a href="http://www.econstor.eu/bitstream/10419/87109/1/577012886.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="giannikis2008modelling">19</a>]
			</td>
			<td class="bibtexitem">
			Dimitris Giannikis, Ioannis&nbsp;D Vrontos, and Petros Dellaportas.
			 Modelling nonlinearities and heavy tails via threshold normal mixture
			  garch models.
			 <em>Computational Statistics &amp; Data Analysis</em>, 52(3):1549-1571,
			  2008.
			[&nbsp;<a href="PD_citations_bib.html#giannikis2008modelling">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0167947307002010">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2007flexible">20</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, David&nbsp;GT Denison, and Chris Holmes.
			 Flexible threshold models for modelling interest rate volatility.
			 <em>Econometric reviews</em>, 26(2-4):419-437, 2007.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2007flexible">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/07474930701220600">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2007modelling">21</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioannis&nbsp;D Vrontos.
			 Modelling volatility asymmetries: a bayesian analysis of a class of
			  tree structured multivariate garch models.
			 <em>The Econometrics Journal</em>, 10(3):503-520, 2007.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2007modelling">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1368-423X.2007.00219.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2006bayesian">22</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Nial Friel, and Gareth&nbsp;O Roberts.
			 Bayesian model selection for partially observed diffusion models.
			 <em>Biometrika</em>, 93(4):809-825, 2006.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2006bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.3173&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2006multivariate">23</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioulia Papageorgiou.
			 Multivariate mixtures of normals with unknown number of components.
			 <em>Statistics and Computing</em>, 16(1):57-68, 2006.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2006multivariate">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.77.9391&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="giakoumatos2005bayesian">24</a>]
			</td>
			<td class="bibtexitem">
			Stefanos&nbsp;G Giakoumatos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 Bayesian analysis of the unobserved arch model.
			 <em>Statistics and Computing</em>, 15(2):103-111, 2005.
			[&nbsp;<a href="PD_citations_bib.html#giakoumatos2005bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-005-6202-9">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2005model">25</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Claudia Tarantola.
			 Model determination for categorical data with factor level merging.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 67(2):269-283, 2005.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2005model">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1467-9868.2005.00501.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="roberts2004bayesian">26</a>]
			</td>
			<td class="bibtexitem">
			Gareth&nbsp;O Roberts, Omiros Papaspiliopoulos, and Petros Dellaportas.
			 Bayesian inference for non-gaussian ornstein-uhlenbeck stochastic
			  volatility processes.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 66(2):369-393, 2004.
			[&nbsp;<a href="PD_citations_bib.html#roberts2004bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1369-7412.2004.05139.x/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="spezia2004periodic">27</a>]
			</td>
			<td class="bibtexitem">
			Luigi Spezia, Roberta Paroli, and Petros Dellaportas.
			 Periodic markov switching autoregressive models for bayesian analysis
			  and forecasting of air pollution.
			 <em>Statistical Modelling</em>, 4(1):19-38, 2004.
			[&nbsp;<a href="PD_citations_bib.html#spezia2004periodic">bib</a>&nbsp;| 
			<a href="http://smj.sagepub.com/content/4/1/19.short">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="stephens2004quantification">28</a>]
			</td>
			<td class="bibtexitem">
			David&nbsp;A Stephens, Martin&nbsp;J Crowder, and Petros Dellaportas.
			 Quantification of automobile insurance liability: a bayesian failure
			  time approach.
			 <em>Insurance: Mathematics and Economics</em>, 34(1):1-21, 2004.
			[&nbsp;<a href="PD_citations_bib.html#stephens2004quantification">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0167668703001999">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2003full">29</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 A full-factor multivariate garch model.
			 <em>The Econometrics Journal</em>, 6(2):312-334, 2003.
			[&nbsp;<a href="PD_citations_bib.html#vrontos2003full">bib</a>&nbsp;| 
			<a href="http://www.feweb.vu.nl/econometriclinks/journal/volume6/VrontosDellaportasPolitis/ectjVrontos.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="linardakis2003assessment">30</a>]
			</td>
			<td class="bibtexitem">
			Michalis Linardakis and Petros Dellaportas.
			 Assessment of Athens's metro passenger behaviour via a multiranked
			  probit model.
			 <em>Journal of the Royal Statistical Society: Series C (Applied
			  Statistics)</em>, 52(2):185-200, 2003.
			[&nbsp;<a href="PD_citations_bib.html#linardakis2003assessment">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/1467-9876.00397/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="bottolo2003bayesian">31</a>]
			</td>
			<td class="bibtexitem">
			Leonardo Bottolo, Guido Consonni, Petros Dellaportas, and Antonio Lijoi.
			 Bayesian analysis of extreme values by mixture modeling.
			 <em>Extremes</em>, 6(1):25-47, 2003.
			[&nbsp;<a href="PD_citations_bib.html#bottolo2003bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1023/A:1026225113154">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2003bayesian">32</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Paolo Giudici, and Gareth Roberts.
			 Bayesian inference for nondecomposable graphical gaussian models.
			 <em>Sankhya: The Indian Journal of Statistics</em>, pages 43-55,
			  2003.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2003bayesian">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Paolo_Giudici/publication/2718442_Bayesian_inference_for_nondecomposable_graphical_Gaussian_models/links/0fcfd50b06ba4b5932000000.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2003bayesian">33</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras, Petros Dellaportas, and Jonathan&nbsp;J Forster.
			 Bayesian variable and link determination for generalised linear
			  models.
			 <em>Journal of statistical planning and inference</em>, 111(1):165-180,
			  2003.
			[&nbsp;<a href="PD_citations_bib.html#ntzoufras2003bayesian">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0378375802002987">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2003inference">34</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 Inference for some multivariate arch and garch models.
			 <em>Journal of Forecasting</em>, 22(6-7):427-446, 2003.
			[&nbsp;<a href="PD_citations_bib.html#vrontos2003inference">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/for.871/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2003introduction">35</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Gareth&nbsp;O Roberts.
			 An introduction to mcmc.
			 In <em>Spatial statistics and computational methods</em>, pages 1-41.
			  Springer New York, 2003.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2003introduction">bib</a>&nbsp;| 
			<a href="http://www.springer.com/us/book/9780387001364">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2002bayesian">36</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras and Petros Dellaportas.
			 Bayesian modelling of outstanding liabilities incorporating claim
			  count uncertainty.
			 <em>North American Actuarial Journal</em>, 6(1):113-125, 2002.
			[&nbsp;<a href="PD_citations_bib.html#ntzoufras2002bayesian">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/10920277.2002.10596032">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2002bayesian">37</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 On bayesian model and variable selection using mcmc.
			 <em>Statistics and Computing</em>, 12(1):27-36, 2002.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2002bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1023/A:1013164120801">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2001application">38</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Stefanos&nbsp;G Giakoumatos, Petros Dellaportas, and Dimitris&nbsp;N
			  Politis.
			 An application of three bivariate time-varying volatility models.
			 <em>Applied stochastic models in business and industry</em>,
			  17(1):121-133, 2001.
			[&nbsp;<a href="PD_citations_bib.html#vrontos2001application">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/asmb.431/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2001simulation">39</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Dimitris Karlis.
			 A simulation approach to nonparametric empirical bayes analysis.
			 <em>International statistical review</em>, 69(1):63-79, 2001.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2001simulation">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1751-5823.2001.tb00480.x/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2001bsimulation">40</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Dimitris Karlis.
			 A simulation approach to hierarchical models.
			 <em>International Statistical Review</em>, 69:63-79, 2001.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2001bsimulation">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Petros_Dellaportas/publication/2702619_A_Simulation_Approach_to_Hierarchical_Models/links/0912f50e54327bb527000000.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kateri2001bayesian">41</a>]
			</td>
			<td class="bibtexitem">
			Maria Kateri, Takis Papaioannou, and Petros Dellaportas.
			 Bayesian analysis of correlated proportions.
			 <em>Sankhya: The Indian Journal of Statistics, Series B</em>, pages
			  270-285, 2001.
			[&nbsp;<a href="PD_citations_bib.html#kateri2001bayesian">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Maria_Kateri2/publication/254778981_BAYESIAN_ANALYSIS_OF_CORRELATED_PROPORTIONS/links/54ca62630cf2517b755e05b1.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2001bayesian">42</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Adrian&nbsp;FM Smith, and Photis Stavropoulos.
			 Bayesian analysis of mortality data.
			 <em>Journal of the Royal Statistical Society: Series A (Statistics
			  in Society)</em>, 164(2):275-291, 2001.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2001bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/1467-985X.00202/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="denison2001wind">43</a>]
			</td>
			<td class="bibtexitem">
			David&nbsp;GT Denison, Petros Dellaportas, and Bani&nbsp;K Mallick.
			 Wind speed prediction in a complex terrain.
			 <em>Environmetrics</em>, 12(6):499-515, 2001.
			[&nbsp;<a href="PD_citations_bib.html#denison2001wind">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/env.480/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2000full">44</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 Full bayesian inference for garch and egarch models.
			 <em>Journal of Business &amp; Economic Statistics</em>, 18(2):187-198,
			  2000.
			[&nbsp;<a href="PD_citations_bib.html#vrontos2000full">bib</a>&nbsp;| 
			<a href="http://amstat.tandfonline.com/doi/abs/10.1080/07350015.2000.10524861">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2000stochastic">45</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras, Jonathan&nbsp;J Forster, and Petros Dellaportas.
			 Stochastic search variable selection for log-linear models.
			 <em>Journal of Statistical Computation and Simulation</em>,
			  68(1):23-37, 2000.
			[&nbsp;<a href="PD_citations_bib.html#ntzoufras2000stochastic">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/00949650008812054">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="linardakis2000approach">46</a>]
			</td>
			<td class="bibtexitem">
			Michalis Linardakis and Petros Dellaportas.
			 An approach to multidimensional item response modeling.
			 In <em>The Sixth World Meeting of the International Society for
			  Bayesian Analysis ISBA</em>, pages 331-340. 2000.
			[&nbsp;<a href="PD_citations_bib.html#linardakis2000approach">bib</a>&nbsp;| 
			<a href="http://hbanaszak.mjr.uw.edu.pl/TempTxt/an-approach-to-multidimensional.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2000bayesian">47</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 Bayesian variable selection using the gibbs sampler.
			 In <em>Biostatistics-Basel</em>, volume&nbsp;5, pages 273-286. Citeseer,
			  2000.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas2000bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.57.4258&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="mouzakis1999fatigue">48</a>]
			</td>
			<td class="bibtexitem">
			Fragiskos Mouzakis, Evaggelos Morfiadakis, and Petros Dellaportas.
			 Fatigue loading parameter identification of a wind turbine operating
			  in complex terrain.
			 <em>Journal of Wind Engineering and Industrial Aerodynamics</em>,
			  82(1):69-88, 1999.
			[&nbsp;<a href="PD_citations_bib.html#mouzakis1999fatigue">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0167610598002116">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="zaphiropoulos1999prediction">49</a>]
			</td>
			<td class="bibtexitem">
			Yiorgos Zaphiropoulos, Petros Dellaportas, Evangelos Morfiadakis, and Georgia
			  Glinou.
			 Prediction of wind speed and direction at a potential site.
			 <em>Wind Engineering</em>, 23(3):167-176, 1999.
			[&nbsp;<a href="PD_citations_bib.html#zaphiropoulos1999prediction">bib</a>&nbsp;| 
			<a href="http://www.multi-science.co.uk/windeng.htm">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="giakoumatos1999markov">50</a>]
			</td>
			<td class="bibtexitem">
			Stefanos&nbsp;G Giakoumatos, Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N
			  Politis.
			 A markov chain monte carlo convergence diagnostic using subsampling.
			 <em>Journal of Computational and Graphical Statistics</em>,
			  8(3):431-451, 1999.
			[&nbsp;<a href="PD_citations_bib.html#giakoumatos1999markov">bib</a>&nbsp;| 
			<a href="http://amstat.tandfonline.com/doi/abs/10.1080/10618600.1999.10474825">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1999markov">51</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Jonathan&nbsp;J Forster.
			 Markov chain monte carlo model determination for hierarchical and
			  graphical log-linear models.
			 <em>Biometrika</em>, 86(3):615-633, 1999.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1999markov">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Petros_Dellaportas/publication/2730071_Markov_Chain_Monte_Carlo_Model_Determination_for_Hierarchical_and_Graphical_Log-linear_Models/links/0912f50e5432796027000000.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1998bayesian">52</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas.
			 Bayesian classification of neolithic tools.
			 <em>Journal of the Royal Statistical Society: Series C (Applied
			  Statistics)</em>, 47(2):279-297, 1998.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1998bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/1467-9876.00112/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="brooks1997approach">53</a>]
			</td>
			<td class="bibtexitem">
			Steve&nbsp;P Brooks, Petros Dellaportas, and Gareth&nbsp;O Roberts.
			 An approach to diagnosing total variation convergence of mcmc
			  algorithms.
			 <em>Journal of Computational and Graphical Statistics</em>,
			  6(3):251-265, 1997.
			[&nbsp;<a href="PD_citations_bib.html#brooks1997approach">bib</a>&nbsp;| 
			<a href="http://amstat.tandfonline.com/doi/abs/10.1080/10618600.1997.10474741">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="cools1996role">54</a>]
			</td>
			<td class="bibtexitem">
			Ronald Cools and Petros Dellaportas.
			 The role of embedded integration rules in bayesian statistics.
			 <em>Statistics and Computing</em>, 6(3):245-250, 1996.
			[&nbsp;<a href="PD_citations_bib.html#cools1996role">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/BF00140868">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1996comparative">55</a>]
			</td>
			<td class="bibtexitem">
			P&nbsp;Dellaportas, DA&nbsp;Stephens, AFM Smith, and I&nbsp;Guttman.
			 A comparative study of perinatal mortality using a two-component
			  mixture model.
			 In <em>Bayesian Biostatistics, (Statistics textbooks and
			  monographs)</em>, volume 151, pages 601-616. Marcel Dekker AG, 1996.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1996comparative">bib</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kokolakis1996hierarchical">56</a>]
			</td>
			<td class="bibtexitem">
			G&nbsp;Kokolakis and P&nbsp;Dellaportas.
			 Hierarchical modelling for classifying binary data.
			 In <em>Bayesian Statistics 5</em>, pages 647-652. 1996.
			[&nbsp;<a href="PD_citations_bib.html#kokolakis1996hierarchical">bib</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1995bayesian">57</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and David&nbsp;A Stephens.
			 Bayesian analysis of errors-in-variables regression models.
			 <em>Biometrics</em>, pages 1085-1095, 1995.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1995bayesian">bib</a>&nbsp;| 
			<a href="http://www.jstor.org/stable/2533007?seq=1#page_scan_tab_contents">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1995random">58</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas.
			 Random variate transformations in the gibbs sampler: Issues of
			  efficiency and convergence.
			 <em>Statistics and Computing</em>, 5(2):133-140, 1995.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1995random">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/BF00143944">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1993bayesian">59</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Adrian&nbsp;FM Smith.
			 Bayesian inference for generalized linear and proportional hazards
			  models via gibbs sampling.
			 <em>Applied Statistics</em>, pages 443-459, 1993.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1993bayesian">bib</a>&nbsp;| 
			<a href="http://www.jstor.org/stable/2986324?seq=1#page_scan_tab_contents">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="data47">60</a>]
			</td>
			<td class="bibtexitem">
			P.&nbsp;Dellaportas and D.&nbsp;Wright.
			 A numerical integration strategy in bayesian analysis.
			 In <em>Bayesian Statistics 4</em>, pages 601-606. 1992.
			[&nbsp;<a href="PD_citations_bib.html#data47">bib</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="stephens1992bayesian">61</a>]
			</td>
			<td class="bibtexitem">
			D&nbsp;Stephens and P&nbsp;Dellaportas.
			 Bayesian analysis of generalised linear models with covariate
			  measurement error.
			 In <em>Bayesian statistics 4</em>, pages 813-820. 1992.
			[&nbsp;<a href="PD_citations_bib.html#stephens1992bayesian">bib</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1991numerical">62</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and David Wright.
			 Numerical prediction for the two-parameter weibull distribution.
			 <em>The Statistician</em>, pages 365-372, 1991.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1991numerical">bib</a>&nbsp;| 
			<a href="http://www.jstor.org/stable/2348725?seq=1#page_scan_tab_contents">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1991positive">63</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and David&nbsp;E Wright.
			 Positive embedded integration in bayesian analysis.
			 <em>Statistics and Computing</em>, 1(1):1-12, 1991.
			[&nbsp;<a href="PD_citations_bib.html#dellaportas1991positive">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/BF01890832">http</a>&nbsp;]

			</td>
			</tr>
			</table>
			
		</div>
		
		
		<div id="applications" style="display: none">
		<table>

			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="rackham2015wgbssuite">1</a>]
			</td>
			<td class="bibtexitem">
			Owen&nbsp;JL Rackham, Petros Dellaportas, Enrico Petretto, and Leonardo Bottolo.
			 Wgbssuite: simulating whole-genome bisulphite sequencing data and
			  benchmarking differential dna methylation analysis tools.
			 <em>Bioinformatics</em>, 31:2371-3, 2015.
			[&nbsp;<a href="PD_applications_bib.html#rackham2015wgbssuite">bib</a>&nbsp;| 
			<a href="http://bioinformatics.oxfordjournals.org/content/early/2015/03/25/bioinformatics.btv114.full.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2014museum">2</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Effie Papageorgiou, and Georgios Panagiaris.
			 Museum factors affecting the ageing process of organic materials:
			  review on experimental designs and the invenvorg project as a pilot study.
			 <em>Heritage Science</em>, 2(1):2, 2014.
			[&nbsp;<a href="PD_applications_bib.html#dellaportas2014museum">bib</a>&nbsp;| 
			<a href="http://www.biomedcentral.com/content/pdf/2050-7445-2-2.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="stephens2004quantification">3</a>]
			</td>
			<td class="bibtexitem">
			David&nbsp;A Stephens, Martin&nbsp;J Crowder, and Petros Dellaportas.
			 Quantification of automobile insurance liability: a bayesian failure
			  time approach.
			 <em>Insurance: Mathematics and Economics</em>, 34(1):1-21, 2004.
			[&nbsp;<a href="PD_applications_bib.html#stephens2004quantification">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0167668703001999">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="spezia2004periodic">4</a>]
			</td>
			<td class="bibtexitem">
			Luigi Spezia, Roberta Paroli, and Petros Dellaportas.
			 Periodic markov switching autoregressive models for bayesian analysis
			  and forecasting of air pollution.
			 <em>Statistical Modelling</em>, 4(1):19-38, 2004.
			[&nbsp;<a href="PD_applications_bib.html#spezia2004periodic">bib</a>&nbsp;| 
			<a href="http://smj.sagepub.com/content/4/1/19.short">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="bottolo2003bayesian">5</a>]
			</td>
			<td class="bibtexitem">
			Leonardo Bottolo, Guido Consonni, Petros Dellaportas, and Antonio Lijoi.
			 Bayesian analysis of extreme values by mixture modeling.
			 <em>Extremes</em>, 6(1):25-47, 2003.
			[&nbsp;<a href="PD_applications_bib.html#bottolo2003bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1023/A:1026225113154">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="linardakis2003assessment">6</a>]
			</td>
			<td class="bibtexitem">
			Michalis Linardakis and Petros Dellaportas.
			 Assessment of Athens's metro passenger behaviour via a multiranked
			  probit model.
			 <em>Journal of the Royal Statistical Society: Series C (Applied
			  Statistics)</em>, 52(2):185-200, 2003.
			[&nbsp;<a href="PD_applications_bib.html#linardakis2003assessment">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/1467-9876.00397/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2002bayesian">7</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras and Petros Dellaportas.
			 Bayesian modelling of outstanding liabilities incorporating claim
			  count uncertainty.
			 <em>North American Actuarial Journal</em>, 6(1):113-125, 2002.
			[&nbsp;<a href="PD_applications_bib.html#ntzoufras2002bayesian">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/10920277.2002.10596032">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2001bayesian">8</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Adrian&nbsp;FM Smith, and Photis Stavropoulos.
			 Bayesian analysis of mortality data.
			 <em>Journal of the Royal Statistical Society: Series A (Statistics
			  in Society)</em>, 164(2):275-291, 2001.
			[&nbsp;<a href="PD_applications_bib.html#dellaportas2001bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/1467-985X.00202/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="denison2001wind">9</a>]
			</td>
			<td class="bibtexitem">
			David&nbsp;GT Denison, Petros Dellaportas, and Bani&nbsp;K Mallick.
			 Wind speed prediction in a complex terrain.
			 <em>Environmetrics</em>, 12(6):499-515, 2001.
			[&nbsp;<a href="PD_applications_bib.html#denison2001wind">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/env.480/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="linardakis2000approach">10</a>]
			</td>
			<td class="bibtexitem">
			Michalis Linardakis and Petros Dellaportas.
			 An approach to multidimensional item response modeling.
			 In <em>The Sixth World Meeting of the International Society for
			  Bayesian Analysis ISBA</em>, pages 331-340. 2000.
			[&nbsp;<a href="PD_applications_bib.html#linardakis2000approach">bib</a>&nbsp;| 
			<a href="http://hbanaszak.mjr.uw.edu.pl/TempTxt/an-approach-to-multidimensional.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1998bayesian">11</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas.
			 Bayesian classification of neolithic tools.
			 <em>Journal of the Royal Statistical Society: Series C (Applied
			  Statistics)</em>, 47(2):279-297, 1998.
			[&nbsp;<a href="PD_applications_bib.html#dellaportas1998bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/1467-9876.00112/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1996comparative">12</a>]
			</td>
			<td class="bibtexitem">
			P&nbsp;Dellaportas, DA&nbsp;Stephens, AFM Smith, and I&nbsp;Guttman.
			 A comparative study of perinatal mortality using a two-component
			  mixture model.
			 In <em>Bayesian Biostatistics, (Statistics textbooks and
			  monographs)</em>, volume 151, pages 601-616. Marcel Dekker AG, 1996.
			[&nbsp;<a href="PD_applications_bib.html#dellaportas1996comparative">bib</a>&nbsp;]

			</td>
			</tr>
		</table>

		</div>
		
		
		<div id="financial" style="display: none">
		<table>

			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="petralias2015volatility">1</a>]
			</td>
			<td class="bibtexitem">
			Athanassios Petralias and Petros Dellaportas.
			 Volatility prediction based on scheduled macroeconomic announcements.
			 <em>Canadian Journal of Statistics</em>, 43:199-223, 2015.
			[&nbsp;<a href="PD_Financial_applications_bib.html#petralias2015volatility">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/cjs.11247/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="andersen2014communication">2</a>]
			</td>
			<td class="bibtexitem">
			J&oslash;rgen&nbsp;Vitting Andersen, Ioannis Vrontos, Petros Dellaportas, and Serge
			  Galam.
			 Communication impacting financial markets.
			 <em>EPL (Europhysics Letters)</em>, 108(2):28007, 2014.
			[&nbsp;<a href="PD_Financial_applications_bib.html#andersen2014communication">bib</a>&nbsp;| 
			<a href="http://arxiv.org/pdf/1410.2550.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2014smile">3</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Aleksandar Mijatovic.
			 Smile transformation for price prediction.
			 <em>Risk</em>, pages 62-67, 2014.
			[&nbsp;<a href="PD_Financial_applications_bib.html#dellaportas2014smile">bib</a>&nbsp;| 
			<a href="http://search.proquest.com/openview/b385394150e73215d07256a9afbe9004/1?pq-origsite=gscholar">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="arakelian2012contagion">4</a>]
			</td>
			<td class="bibtexitem">
			Veni Arakelian and Petros Dellaportas.
			 Contagion determination via copula and volatility threshold models.
			 <em>Quantitative Finance</em>, 12(2):295-310, 2012.
			[&nbsp;<a href="PD_Financial_applications_bib.html#arakelian2012contagion">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/14697680903410023">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012cholesky">5</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Mohsen Pourahmadi.
			 Cholesky-garch models with applications to finance.
			 <em>Statistics and Computing</em>, 22(4):849-855, 2012.
			[&nbsp;<a href="PD_Financial_applications_bib.html#dellaportas2012cholesky">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-011-9251-2">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="meligkotsidou2011forecasting">6</a>]
			</td>
			<td class="bibtexitem">
			Loukia Meligkotsidou and Petros Dellaportas.
			 Forecasting with non-homogeneous hidden markov models.
			 <em>Statistics and Computing</em>, 21(3):439-449, 2011.
			[&nbsp;<a href="PD_Financial_applications_bib.html#meligkotsidou2011forecasting">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-010-9180-5">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kalogeropoulos2011likelihood">7</a>]
			</td>
			<td class="bibtexitem">
			Konstantinos Kalogeropoulos, Petros Dellaportas, and Gareth&nbsp;O Roberts.
			 Likelihood-based inference for correlated diffusions.
			 <em>Canadian journal of statistics</em>, 39(1):52-72, 2011.
			[&nbsp;<a href="PD_Financial_applications_bib.html#kalogeropoulos2011likelihood">bib</a>&nbsp;| 
			<a href="http://economics.ouls.ox.ac.uk/11898/1/chibpittshephard.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kalogeropoulos2010inference">8</a>]
			</td>
			<td class="bibtexitem">
			Konstantinos Kalogeropoulos, Gareth&nbsp;O Roberts, and Petros Dellaportas.
			 Inference for stochastic volatility models using time change
			  transformations.
			 <em>The Annals of Statistics</em>, pages 784-807, 2010.
			[&nbsp;<a href="PD_Financial_applications_bib.html#kalogeropoulos2010inference">bib</a>&nbsp;| 
			<a href="http://projecteuclid.org/download/pdfview_1/euclid.aos/1266586614">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="giannikis2008modelling">9</a>]
			</td>
			<td class="bibtexitem">
			Dimitris Giannikis, Ioannis&nbsp;D Vrontos, and Petros Dellaportas.
			 Modelling nonlinearities and heavy tails via threshold normal mixture
			  garch models.
			 <em>Computational Statistics &amp; Data Analysis</em>, 52(3):1549-1571,
			  2008.
			[&nbsp;<a href="PD_Financial_applications_bib.html#giannikis2008modelling">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0167947307002010">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2007modelling">10</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioannis&nbsp;D Vrontos.
			 Modelling volatility asymmetries: a bayesian analysis of a class of
			  tree structured multivariate garch models.
			 <em>The Econometrics Journal</em>, 10(3):503-520, 2007.
			[&nbsp;<a href="PD_Financial_applications_bib.html#dellaportas2007modelling">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1368-423X.2007.00219.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2007flexible">11</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, David&nbsp;GT Denison, and Chris Holmes.
			 Flexible threshold models for modelling interest rate volatility.
			 <em>Econometric reviews</em>, 26(2-4):419-437, 2007.
			[&nbsp;<a href="PD_Financial_applications_bib.html#dellaportas2007flexible">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/07474930701220600">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="arakelian2006contagion">12</a>]
			</td>
			<td class="bibtexitem">
			Veni Arakelian and Petros Dellaportas.
			 Contagion tests via copula threshold models.
			 <em>Working Paper, University of Athens</em>, 2006.
			[&nbsp;<a href="PD_Financial_applications_bib.html#arakelian2006contagion">bib</a>&nbsp;| 
			<a href="http://stat-athens.aueb.gr/~ptd/copulas.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2006bayesian">13</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Nial Friel, and Gareth&nbsp;O Roberts.
			 Bayesian model selection for partially observed diffusion models.
			 <em>Biometrika</em>, 93(4):809-825, 2006.
			[&nbsp;<a href="PD_Financial_applications_bib.html#dellaportas2006bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.3173&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="giakoumatos2005bayesian">14</a>]
			</td>
			<td class="bibtexitem">
			Stefanos&nbsp;G Giakoumatos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 Bayesian analysis of the unobserved arch model.
			 <em>Statistics and Computing</em>, 15(2):103-111, 2005.
			[&nbsp;<a href="PD_Financial_applications_bib.html#giakoumatos2005bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-005-6202-9">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="roberts2004bayesian">15</a>]
			</td>
			<td class="bibtexitem">
			Gareth&nbsp;O Roberts, Omiros Papaspiliopoulos, and Petros Dellaportas.
			 Bayesian inference for non-gaussian ornstein-uhlenbeck stochastic
			  volatility processes.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 66(2):369-393, 2004.
			[&nbsp;<a href="PD_Financial_applications_bib.html#roberts2004bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1369-7412.2004.05139.x/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2003full">16</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 A full-factor multivariate garch model.
			 <em>The Econometrics Journal</em>, 6(2):312-334, 2003.
			[&nbsp;<a href="PD_Financial_applications_bib.html#vrontos2003full">bib</a>&nbsp;| 
			<a href="http://www.feweb.vu.nl/econometriclinks/journal/volume6/VrontosDellaportasPolitis/ectjVrontos.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2003inference">17</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 Inference for some multivariate arch and garch models.
			 <em>Journal of Forecasting</em>, 22(6-7):427-446, 2003.
			[&nbsp;<a href="PD_Financial_applications_bib.html#vrontos2003inference">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/for.871/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2001application">18</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Stefanos&nbsp;G Giakoumatos, Petros Dellaportas, and Dimitris&nbsp;N
			  Politis.
			 An application of three bivariate time-varying volatility models.
			 <em>Applied stochastic models in business and industry</em>,
			  17(1):121-133, 2001.
			[&nbsp;<a href="PD_Financial_applications_bib.html#vrontos2001application">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1002/asmb.431/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="vrontos2000full">19</a>]
			</td>
			<td class="bibtexitem">
			Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N Politis.
			 Full bayesian inference for garch and egarch models.
			 <em>Journal of Business &amp; Economic Statistics</em>, 18(2):187-198,
			  2000.
			[&nbsp;<a href="PD_Financial_applications_bib.html#vrontos2000full">bib</a>&nbsp;| 
			<a href="http://amstat.tandfonline.com/doi/abs/10.1080/07350015.2000.10524861">http</a>&nbsp;]

			</td>
			</tr>
		</table>		
		</div>
		
		
		<div id="model" style="display: none">

		<table>

			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="petralias2013mcmc">1</a>]
			</td>
			<td class="bibtexitem">
			Athanassios Petralias and Petros Dellaportas.
			 An mcmc model search algorithm for regression problems.
			 <em>Journal of Statistical Computation and Simulation</em>,
			  83(9):1722-1740, 2013.
			[&nbsp;<a href="PD_model_determination_bib.html#petralias2013mcmc">bib</a>&nbsp;| 
			<a href="https://www.tol-project.org/svn/tolp/OfficialTolArchiveNetwork/ArimaTools/doc/bibliografia/MCMC/An%20MCMC%20model%20search%20algorithm%20for.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012joint">2</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 Joint specification of model space and parameter space prior
			  distributions.
			 <em>Statistical Science</em>, 27(2):232-246, 2012.
			[&nbsp;<a href="PD_model_determination_bib.html#dellaportas2012joint">bib</a>&nbsp;| 
			<a href="http://arxiv.org/pdf/1207.5651.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="papathomas2011novel">3</a>]
			</td>
			<td class="bibtexitem">
			Michalis Papathomas, Petros Dellaportas, and Vasilis&nbsp;GS Vasdekis.
			 A novel reversible jump algorithm for generalized linear models.
			 <em>Biometrika</em>, 98(1):231-236, 2011.
			[&nbsp;<a href="PD_model_determination_bib.html#papathomas2011novel">bib</a>&nbsp;| 
			<a href="http://biomet.oxfordjournals.org/content/early/2011/02/06/biomet.asq071.short">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2006bayesian">4</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Nial Friel, and Gareth&nbsp;O Roberts.
			 Bayesian model selection for partially observed diffusion models.
			 <em>Biometrika</em>, 93(4):809-825, 2006.
			[&nbsp;<a href="PD_model_determination_bib.html#dellaportas2006bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.3173&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2005model">5</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Claudia Tarantola.
			 Model determination for categorical data with factor level merging.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 67(2):269-283, 2005.
			[&nbsp;<a href="PD_model_determination_bib.html#dellaportas2005model">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1467-9868.2005.00501.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2003bayesian">6</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras, Petros Dellaportas, and Jonathan&nbsp;J Forster.
			 Bayesian variable and link determination for generalised linear
			  models.
			 <em>Journal of statistical planning and inference</em>, 111(1):165-180,
			  2003.
			[&nbsp;<a href="PD_model_determination_bib.html#ntzoufras2003bayesian">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0378375802002987">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2002bayesian">7</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 On bayesian model and variable selection using mcmc.
			 <em>Statistics and Computing</em>, 12(1):27-36, 2002.
			[&nbsp;<a href="PD_model_determination_bib.html#dellaportas2002bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1023/A:1013164120801">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2000bayesian">8</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 Bayesian variable selection using the gibbs sampler.
			 In <em>Biostatistics-Basel</em>, volume&nbsp;5, pages 273-286. Citeseer,
			  2000.
			[&nbsp;<a href="PD_model_determination_bib.html#dellaportas2000bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.57.4258&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2000stochastic">9</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras, Jonathan&nbsp;J Forster, and Petros Dellaportas.
			 Stochastic search variable selection for log-linear models.
			 <em>Journal of Statistical Computation and Simulation</em>,
			  68(1):23-37, 2000.
			[&nbsp;<a href="PD_model_determination_bib.html#ntzoufras2000stochastic">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/00949650008812054">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1999markov">10</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Jonathan&nbsp;J Forster.
			 Markov chain monte carlo model determination for hierarchical and
			  graphical log-linear models.
			 <em>Biometrika</em>, 86(3):615-633, 1999.
			[&nbsp;<a href="PD_model_determination_bib.html#dellaportas1999markov">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Petros_Dellaportas/publication/2730071_Markov_Chain_Monte_Carlo_Model_Determination_for_Hierarchical_and_Graphical_Log-linear_Models/links/0912f50e5432796027000000.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>
		</table>

		</div>
		
		
		<div id="methodology" style="display: none">

		<table>

			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="rackham2015wgbssuite">1</a>]
			</td>
			<td class="bibtexitem">
			Owen&nbsp;JL Rackham, Petros Dellaportas, Enrico Petretto, and Leonardo Bottolo.
			 Wgbssuite: simulating whole-genome bisulphite sequencing data and
			  benchmarking differential dna methylation analysis tools.
			 <em>Bioinformatics</em>, 31:2371-3, 2015.
			[&nbsp;<a href="PD_methodology_bib.html#rackham2015wgbssuite">bib</a>&nbsp;| 
			<a href="http://bioinformatics.oxfordjournals.org/content/early/2015/03/25/bioinformatics.btv114.full.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="petralias2013mcmc">2</a>]
			</td>
			<td class="bibtexitem">
			Athanassios Petralias and Petros Dellaportas.
			 An mcmc model search algorithm for regression problems.
			 <em>Journal of Statistical Computation and Simulation</em>,
			  83(9):1722-1740, 2013.
			[&nbsp;<a href="PD_methodology_bib.html#petralias2013mcmc">bib</a>&nbsp;| 
			<a href="https://www.tol-project.org/svn/tolp/OfficialTolArchiveNetwork/ArimaTools/doc/bibliografia/MCMC/An%20MCMC%20model%20search%20algorithm%20for.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012control">3</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioannis Kontoyiannis.
			 Control variates for estimation based on reversible markov chain
			  monte carlo samplers.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 74(1):133-161, 2012.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2012control">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1467-9868.2011.01000.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kateri2012conditional">4</a>]
			</td>
			<td class="bibtexitem">
			Maria Kateri and Petros Dellaportas.
			 Conditional symmetry models for three-way contingency tables.
			 <em>Journal of Statistical Planning and Inference</em>,
			  142(8):2430-2439, 2012.
			[&nbsp;<a href="PD_methodology_bib.html#kateri2012conditional">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0378375812000730">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2012joint">5</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 Joint specification of model space and parameter space prior
			  distributions.
			 <em>Statistical Science</em>, 27(2):232-246, 2012.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2012joint">bib</a>&nbsp;| 
			<a href="http://arxiv.org/pdf/1207.5651.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="papathomas2011novel">6</a>]
			</td>
			<td class="bibtexitem">
			Michalis Papathomas, Petros Dellaportas, and Vasilis&nbsp;GS Vasdekis.
			 A novel reversible jump algorithm for generalized linear models.
			 <em>Biometrika</em>, 98(1):231-236, 2011.
			[&nbsp;<a href="PD_methodology_bib.html#papathomas2011novel">bib</a>&nbsp;| 
			<a href="http://biomet.oxfordjournals.org/content/early/2011/02/06/biomet.asq071.short">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="meligkotsidou2011forecasting">7</a>]
			</td>
			<td class="bibtexitem">
			Loukia Meligkotsidou and Petros Dellaportas.
			 Forecasting with non-homogeneous hidden markov models.
			 <em>Statistics and Computing</em>, 21(3):439-449, 2011.
			[&nbsp;<a href="PD_methodology_bib.html#meligkotsidou2011forecasting">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/s11222-010-9180-5">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kalogeropoulos2011likelihood">8</a>]
			</td>
			<td class="bibtexitem">
			Konstantinos Kalogeropoulos, Petros Dellaportas, and Gareth&nbsp;O Roberts.
			 Likelihood-based inference for correlated diffusions.
			 <em>Canadian journal of statistics</em>, 39(1):52-72, 2011.
			[&nbsp;<a href="PD_methodology_bib.html#kalogeropoulos2011likelihood">bib</a>&nbsp;| 
			<a href="http://economics.ouls.ox.ac.uk/11898/1/chibpittshephard.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kalogeropoulos2010inference">9</a>]
			</td>
			<td class="bibtexitem">
			Konstantinos Kalogeropoulos, Gareth&nbsp;O Roberts, and Petros Dellaportas.
			 Inference for stochastic volatility models using time change
			  transformations.
			 <em>The Annals of Statistics</em>, pages 784-807, 2010.
			[&nbsp;<a href="PD_methodology_bib.html#kalogeropoulos2010inference">bib</a>&nbsp;| 
			<a href="http://projecteuclid.org/download/pdfview_1/euclid.aos/1266586614">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2010control">10</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioannis Kontoyiannis.
			 Control variates for reversible mcmc samplers.
			 <em>arXiv preprint arXiv:1008.1355</em>, 2010.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2010control">bib</a>&nbsp;| 
			<a href="http://arxiv.org/abs/1008.1355">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="tarantola2008bayesian">11</a>]
			</td>
			<td class="bibtexitem">
			Claudia Tarantola, Guido Consonni, and Petros Dellaportas.
			 Bayesian clustering for row effects models.
			 <em>Journal of Statistical Planning and Inference</em>,
			  138(7):2223-2235, 2008.
			[&nbsp;<a href="PD_methodology_bib.html#tarantola2008bayesian">bib</a>&nbsp;| 
			<a href="http://www.econstor.eu/bitstream/10419/87109/1/577012886.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2006multivariate">12</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Ioulia Papageorgiou.
			 Multivariate mixtures of normals with unknown number of components.
			 <em>Statistics and Computing</em>, 16(1):57-68, 2006.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2006multivariate">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.77.9391&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2006bayesian">13</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Nial Friel, and Gareth&nbsp;O Roberts.
			 Bayesian model selection for partially observed diffusion models.
			 <em>Biometrika</em>, 93(4):809-825, 2006.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2006bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.3173&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2005model">14</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Claudia Tarantola.
			 Model determination for categorical data with factor level merging.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 67(2):269-283, 2005.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2005model">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1467-9868.2005.00501.x/pdf?userIsAuthenticated=false&deniedAccessCustomisedMessage=">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="roberts2004bayesian">15</a>]
			</td>
			<td class="bibtexitem">
			Gareth&nbsp;O Roberts, Omiros Papaspiliopoulos, and Petros Dellaportas.
			 Bayesian inference for non-gaussian ornstein-uhlenbeck stochastic
			  volatility processes.
			 <em>Journal of the Royal Statistical Society: Series B (Statistical
			  Methodology)</em>, 66(2):369-393, 2004.
			[&nbsp;<a href="PD_methodology_bib.html#roberts2004bayesian">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1369-7412.2004.05139.x/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2003introduction">16</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Gareth&nbsp;O Roberts.
			 An introduction to mcmc.
			 In <em>Spatial statistics and computational methods</em>, pages 1-41.
			  Springer New York, 2003.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2003introduction">bib</a>&nbsp;| 
			<a href="http://www.springer.com/us/book/9780387001364">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="bottolo2003bayesian">17</a>]
			</td>
			<td class="bibtexitem">
			Leonardo Bottolo, Guido Consonni, Petros Dellaportas, and Antonio Lijoi.
			 Bayesian analysis of extreme values by mixture modeling.
			 <em>Extremes</em>, 6(1):25-47, 2003.
			[&nbsp;<a href="PD_methodology_bib.html#bottolo2003bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1023/A:1026225113154">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2003bayesian">18</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Paolo Giudici, and Gareth Roberts.
			 Bayesian inference for nondecomposable graphical gaussian models.
			 <em>Sankhya: The Indian Journal of Statistics</em>, pages 43-55,
			  2003.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2003bayesian">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Paolo_Giudici/publication/2718442_Bayesian_inference_for_nondecomposable_graphical_Gaussian_models/links/0fcfd50b06ba4b5932000000.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2003bayesian">19</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras, Petros Dellaportas, and Jonathan&nbsp;J Forster.
			 Bayesian variable and link determination for generalised linear
			  models.
			 <em>Journal of statistical planning and inference</em>, 111(1):165-180,
			  2003.
			[&nbsp;<a href="PD_methodology_bib.html#ntzoufras2003bayesian">bib</a>&nbsp;| 
			<a href="http://www.sciencedirect.com/science/article/pii/S0378375802002987">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2002bayesian">20</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 On bayesian model and variable selection using mcmc.
			 <em>Statistics and Computing</em>, 12(1):27-36, 2002.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2002bayesian">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1023/A:1013164120801">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="kateri2001bayesian">21</a>]
			</td>
			<td class="bibtexitem">
			Maria Kateri, Takis Papaioannou, and Petros Dellaportas.
			 Bayesian analysis of correlated proportions.
			 <em>Sankhya: The Indian Journal of Statistics, Series B</em>, pages
			  270-285, 2001.
			[&nbsp;<a href="PD_methodology_bib.html#kateri2001bayesian">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Maria_Kateri2/publication/254778981_BAYESIAN_ANALYSIS_OF_CORRELATED_PROPORTIONS/links/54ca62630cf2517b755e05b1.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2001simulation">23</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Dimitris Karlis.
			 A simulation approach to nonparametric empirical bayes analysis.
			 <em>International statistical review</em>, 69(1):63-79, 2001.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2001simulation">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1751-5823.2001.tb00480.x/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2001simulation">23</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Dimitris Karlis.
			 A simulation approach to nonparametric empirical bayes analysis.
			 <em>International statistical review</em>, 69(1):63-79, 2001.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2001simulation">bib</a>&nbsp;| 
			<a href="http://onlinelibrary.wiley.com/doi/10.1111/j.1751-5823.2001.tb00480.x/pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2000bayesian">24</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas, Jonathan&nbsp;J Forster, and Ioannis Ntzoufras.
			 Bayesian variable selection using the gibbs sampler.
			 In <em>Biostatistics-Basel</em>, volume&nbsp;5, pages 273-286. Citeseer,
			  2000.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas2000bayesian">bib</a>&nbsp;| 
			<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.57.4258&rep=rep1&type=pdf">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="ntzoufras2000stochastic">25</a>]
			</td>
			<td class="bibtexitem">
			Ioannis Ntzoufras, Jonathan&nbsp;J Forster, and Petros Dellaportas.
			 Stochastic search variable selection for log-linear models.
			 <em>Journal of Statistical Computation and Simulation</em>,
			  68(1):23-37, 2000.
			[&nbsp;<a href="PD_methodology_bib.html#ntzoufras2000stochastic">bib</a>&nbsp;| 
			<a href="http://www.tandfonline.com/doi/abs/10.1080/00949650008812054">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="linardakis2000approach">26</a>]
			</td>
			<td class="bibtexitem">
			Michalis Linardakis and Petros Dellaportas.
			 An approach to multidimensional item response modeling.
			 In <em>The Sixth World Meeting of the International Society for
			  Bayesian Analysis ISBA</em>, pages 331-340. 2000.
			[&nbsp;<a href="PD_methodology_bib.html#linardakis2000approach">bib</a>&nbsp;| 
			<a href="http://hbanaszak.mjr.uw.edu.pl/TempTxt/an-approach-to-multidimensional.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1999markov">27</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Jonathan&nbsp;J Forster.
			 Markov chain monte carlo model determination for hierarchical and
			  graphical log-linear models.
			 <em>Biometrika</em>, 86(3):615-633, 1999.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas1999markov">bib</a>&nbsp;| 
			<a href="http://www.researchgate.net/profile/Petros_Dellaportas/publication/2730071_Markov_Chain_Monte_Carlo_Model_Determination_for_Hierarchical_and_Graphical_Log-linear_Models/links/0912f50e5432796027000000.pdf">.pdf</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="giakoumatos1999markov">28</a>]
			</td>
			<td class="bibtexitem">
			Stefanos&nbsp;G Giakoumatos, Ioannis&nbsp;D Vrontos, Petros Dellaportas, and Dimitris&nbsp;N
			  Politis.
			 A markov chain monte carlo convergence diagnostic using subsampling.
			 <em>Journal of Computational and Graphical Statistics</em>,
			  8(3):431-451, 1999.
			[&nbsp;<a href="PD_methodology_bib.html#giakoumatos1999markov">bib</a>&nbsp;| 
			<a href="http://amstat.tandfonline.com/doi/abs/10.1080/10618600.1999.10474825">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="brooks1997approach">29</a>]
			</td>
			<td class="bibtexitem">
			Steve&nbsp;P Brooks, Petros Dellaportas, and Gareth&nbsp;O Roberts.
			 An approach to diagnosing total variation convergence of mcmc
			  algorithms.
			 <em>Journal of Computational and Graphical Statistics</em>,
			  6(3):251-265, 1997.
			[&nbsp;<a href="PD_methodology_bib.html#brooks1997approach">bib</a>&nbsp;| 
			<a href="http://amstat.tandfonline.com/doi/abs/10.1080/10618600.1997.10474741">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="cools1996role">30</a>]
			</td>
			<td class="bibtexitem">
			Ronald Cools and Petros Dellaportas.
			 The role of embedded integration rules in bayesian statistics.
			 <em>Statistics and Computing</em>, 6(3):245-250, 1996.
			[&nbsp;<a href="PD_methodology_bib.html#cools1996role">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/BF00140868">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1995bayesian">31</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and David&nbsp;A Stephens.
			 Bayesian analysis of errors-in-variables regression models.
			 <em>Biometrics</em>, pages 1085-1095, 1995.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas1995bayesian">bib</a>&nbsp;| 
			<a href="http://www.jstor.org/stable/2533007?seq=1#page_scan_tab_contents">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1995random">32</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas.
			 Random variate transformations in the gibbs sampler: Issues of
			  efficiency and convergence.
			 <em>Statistics and Computing</em>, 5(2):133-140, 1995.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas1995random">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/BF00143944">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1993bayesian">33</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Adrian&nbsp;FM Smith.
			 Bayesian inference for generalized linear and proportional hazards
			  models via gibbs sampling.
			 <em>Applied Statistics</em>, pages 443-459, 1993.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas1993bayesian">bib</a>&nbsp;| 
			<a href="http://www.jstor.org/stable/2986324?seq=1#page_scan_tab_contents">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="stephens1992bayesian">34</a>]
			</td>
			<td class="bibtexitem">
			D&nbsp;Stephens and P&nbsp;Dellaportas.
			 Bayesian analysis of generalised linear models with covariate
			  measurement error.
			 In <em>Bayesian statistics 4</em>, pages 813-820. 1992.
			[&nbsp;<a href="PD_methodology_bib.html#stephens1992bayesian">bib</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1991numerical">35</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and David Wright.
			 Numerical prediction for the two-parameter weibull distribution.
			 <em>The Statistician</em>, pages 365-372, 1991.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas1991numerical">bib</a>&nbsp;| 
			<a href="http://www.jstor.org/stable/2348725?seq=1#page_scan_tab_contents">http</a>&nbsp;]

			</td>
			</tr>


			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas1991positive">36</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and David&nbsp;E Wright.
			 Positive embedded integration in bayesian analysis.
			 <em>Statistics and Computing</em>, 1(1):1-12, 1991.
			[&nbsp;<a href="PD_methodology_bib.html#dellaportas1991positive">bib</a>&nbsp;| 
			<a href="http://link.springer.com/article/10.1007/BF01890832">http</a>&nbsp;]

			</td>
			</tr>
		</table>
		
		</div>
		
		
		<div id="book" style="display: none">
		
		<table>

			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="damien2013bayesian">1</a>]
			</td>
			<td class="bibtexitem">
			Paul Damien, Petros Dellaportas, Nicholas&nbsp;G Polson, and David&nbsp;A Stephens.
			 <em>Bayesian Theory and Applications</em>.
			 Oxford University Press, 2013.
			[&nbsp;<a href="PD_book_bib.html#damien2013bayesian">bib</a>&nbsp;| 
			<a href="http://ukcatalogue.oup.com/product/9780199695607.do">http</a>&nbsp;]

			</td>
			</tr>
		</table>
		
		</div>
		
		
		<div id="notes" style="display: none">
		<table>

			<tr valign="top">
			<td align="right" class="bibtexnumber">
			[<a name="dellaportas2003introduction">1</a>]
			</td>
			<td class="bibtexitem">
			Petros Dellaportas and Gareth&nbsp;O Roberts.
			 An introduction to MCMC.
			 In <em>Spatial statistics and computational methods</em>, pages 1-41.
			  Springer New York, 2003.
			[&nbsp;<a href="PD_notes_bib.html#dellaportas2003introduction">bib</a>&nbsp;| 
			<a href="http://www.springer.com/us/book/9780387001364">http</a>&nbsp;]

			</td>
			</tr>
		</table>
		</div>
	</div>
			
</div>

<!---------- Students -------------->

<div id="students" style="display: none">
	
	<b> Post-doctoral students: </b> 
	<br> <br> 	
	<ol>
		<li>   Anastasios Plataniotis, 2013-2015 </li>
		<li>  <a href="http://www.stat-athens.aueb.gr/~apet/"> Athanassios Petralias </a> , 2013 </li>
		<li>   Ioannis Dendramis  (jointly supervised with <a href="http://www.econ.upf.edu/~omiros/">  Omiros Papaspiliopoulos </a>), 2013 </li>
		<li>   <a href="http://users.uoa.gr/~meligots/"> Loukia Meligotsidou </a>, 2007-2008 </li>
		<li>   <a href="http://www.imperial.ac.uk/people/m.papathomas"> Michalis Papathomas</a> (jointly supervised with <a href="http://stat-athens.aueb.gr/~vasdekis/"> Vassilis Vasdekis</a> ), 2004-2006 </li>
		<li>   <a href="http://stat-athens.aueb.gr/~ioulia/"> Ioulia Papageorgiou </a> , 2002-2003 </li>
		<li>   <a href="http://www.imperial.ac.uk/people/l.bottolo"> Leonardo Bottolo </a> , 2002 </li>
		<li>   <a href="http://www.bioss.ac.uk/people/luigi.html"> Luigi Spezia  </a> , 2001 </li>
		<li>   <a href="http://mathsci.ucd.ie/~nial/"> Nial Friel </a>,  2000 </li>
		<li>   <a href="http://economia.unipv.it/pagp/pagine_personali/ctaranto/tarantola.htm"> Claudia Tarantola  </a>, 1999 </li>
		<li>   <a href="http://www.unive.it/data/persone/5592702"> Stefano Tonellato  </a>, 1998 </li>
	</ol>	
	<br> <br> <br> 
	<b> PhD students: </b> 
	<br> <br> 	
	<ol>
		<li> <a href="https://uk.linkedin.com/pub/jacopo-thomas-capra/3/674/702"> Jacopo Thomas Capra</a> -- "Portfolio construction with macro views", current, UCL </li>
		<li> <a href="https://www.linkedin.com/in/marcel-hirt-795aab68"> Marcel Hirt </a> -- "Price impact in high frequency markets", current, UCL </li>
		<li> Aris Panos -- "Covariance kernels for big data", current, UCL </li>	
		<li> Zhongzhen Wang -- "Tensor factorisations for event sequence forecasting"  (jointly supervised with <a href="https://www.ucl.ac.uk/statistics/people/ioanniskosmidis"> Ioannis Kosmidis </a>), current, UCL </li>	
<li> Santhosh Narayanan -- "Point processes for sports modelling"  (jointly supervised with <a href="https://www.ucl.ac.uk/statistics/people/ioanniskosmidis"> Ioannis Kosmidis </a>), current, Warwick </li>	
		<li> Fiori Labrinakou -- "Modelling of High frequency trading", current,AUEB </li>
		<li> Aggelos Alexopoulos -- "Bayesian modelling of high dimensional financial data using latent Gaussian models",2017 </li>
		<li> Zoe Tsourti -- "Issues of Markov Chain Monte Carlo", 2012 </li>
		<li> <a href="http://www.stat-athens.aueb.gr/~apet/"> Athanassios Petralias </a> -- "Bayesian Model Determination and Nonlinear Threshold Volatility Models", 2011 </li>
		<li> Anastasios Plataniotis -- "Multivariate Stochastic Volatility Models", 2011 </li>
		<li> <a href="http://stats.lse.ac.uk/kalogeropoulos/"> Konstantinos Kalogeropoulos</a> -- "Bayesian Inference for Multidimensional Diffusion Processes", 2007  Savage Award </li>
		<li> <a href="http://sparti.uop.gr/~stefanos/indexEN.htm"> Stefanos Giakoumatos </a> -- "Auxiliary Variable Sampling for Some Time-Varying Volatility Models", 2004</li>
		<li> <a href="http://www.edc.uoc.gr/ptpe/index.php?option=com_content&view=article&id=459&Itemid=538">Michalis Linardakis </a> -- "Extensions of Latent Variable Models with Applications on Econometric and Educational Models", 2004</li>
		<li> <a href="http://stat-athens.aueb.gr/~vrontos/"> Ioannis Vrontos </a>-- "MCMC Applications in Time-Varying Volatility Models", 2001 </li>
		<li> <a href="http://www.stat-athens.aueb.gr/~jbn/ntzoufras.html"> Ioannis Ntzoufras </a> -- "Aspects of Bayesian Model and Variable Selection Using MCMC", 1999 </li>
	</ol>
</div>
 
<!----------Editorial work -------------->

<div id="editor" style="display: none">

    <p class="cal"> co-Editor for </p>
    <ul>
        <li> <a href="https://projecteuclid.org/euclid.ba">Bayesian Analysis</a> (2019-present) </li>  <br><br>
    </ul>
	<p class="cal"> Associate Editor for </p>
	<ul>
		<li> <a href="http://biomet.oxfordjournals.org/">Biometrika</a> (2012-present) </li>  <br><br>
		<li> <a href="http://imstat.org/ejs/">Electronic journal of Statistics</a> (2012-present) </li> <br><br>
		<li> <a href="http://link.springer.com/journal/11222">Statistics and Computing: An international Journal </a> (2001-2012) </li> <br><br>
		<li> <a href="http://onlinelibrary.wiley.com/journal/10.1111/(ISSN)1467-9884"> Journal of the Royal statistical Society -series D </a> (1996-2000) </li> <br><br>	
		<li> <a href="http://www.statmod.org/journal.htm"> Statistical modeling: An international Journal</a> (2001-2007) </li> <br>
	</ul>

	<p class="cal"> Member of the Advisory board of <a href="http://www.tandfonline.com/loi/cjas20#.VgTxPN-qpBc">Journal of Applied Statistics</a>  (2007-present)</p>

</div>

 
 <!--------------------GrStochastics-------------------------->
<div id="grst"  style="display: none">

<div id="pics"> <a href="http://thalesandfriends.org/"> <img src="gs.png"> </a> </div>
	<br><br>
	
	<p>
	I am a founder member of the <a href="http://www.stochastics.gr/"> Greek Stochastics </a> which is a team of Greek Statisticians with overlapping research interests and coalescent research genealogy. 
	On a voluntary basis, we organise a yearly summer workshop in Greece that includes short courses, contributed talks and poster presentations. The other members of Greek Stochastics team are
	<a href="http://www.homepages.ucl.ac.uk/~ucakabe/">Alex Beskos</a>,  
	<a href="http://www.mrc-bsu.cam.ac.uk/personal/nikolaos/">Nikos 
	Demiris</a>, 	<a href="http://stats.lse.ac.uk/kalogeropoulos/">Kostas 
	Kalogeropoulos</a>, 
<a href="https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/kosmidis/">Ioannis Kosmidis</a>,
<a href="https://www.imperial.ac.uk/people/n.kantas">NIkolas Kantas</a>,	<a href="http://www.maths.nottingham.ac.uk/~tk">Theo 
	Kypraios</a>,  and 	<a href="http://www.econ.upf.es/~omiros">Omiros 
	Papaspiliopoulos</a>.
	
		</p>
	<br><br>
	
	<ul>
		<li><a href="http://www.stochastics.gr/meetings/alpha/index.html"> Greek Stochastics &#945;</a>: Monte Carlo: Probability and Methods</li> <br>
		<li><a href="http://www.stochastics.gr/meetings/beta/index.html"> Greek Stochastics &#946;</a>: Interaction between Biology and Probabilistic/Statistical Theory and Methods</li> <br>
		<li><a href="http://www.stochastics.gr/meetings/gamma/index.html"> Greek Stochastics &#947; </a>: Markov Chain Monte Carlo methods</li><br>
		<li><a href="http://www.stochastics.gr/meetings/delta/index.html"> Greek Stochastics &#948; </a>: Inference for Dynamical Systems</li> <br>
		<li><a href="http://www.stochastics.gr/meetings/epsilon/index.html"> Greek Stochastics &#949; </a>: Jump processes: probability, statistical inference and financial modelling</li><br>
		<li><a href="http://www.stochastics.gr/meetings/zeta/index.html"> Greek Stochastics &#950;</a>:  Networks: Theory, Methods and Applications</li> <br>
		<li><a href="http://www.stochastics.gr/meetings/eta/index.html"> Greek Stochastics &#951; </a>: Sequential and On-line Learning</li><br>
<li><a href="http://www.stochastics.gr/meetings/theta/index.html"> Greek Stochastics &#952; </a>: Big Data and Models</li><br>
<li><a href="http://www.stochastics.gr/meetings/iota/"> Greek Stochastics &#953; </a>: Model detrmination</li>
<br>
<li><a href="http://www.stochastics.gr/meetings/kappa/"> Greek Stochastics κ </a>: Statistical Learning</li>
<br>
<li><a href="http://www.stochastics.gr/meetings/lambda/"> Greek Stochastics λ </a>: Stochastic processes and computation</li>
<br>
	</ul>
</div>
 
 
 <!--------------------Thales-------------------------->
  
<div id="thales"  style="display: none">

<div id="pics"> <a href="http://thalesandfriends.org/"> <img src="thales.png"> </a>	</div>
	<br><br>
	
	<p>
	I am a co-founder -- together with the writer <a href="http://www.apostolosdoxiadis.com//"> Apostolos Doxiadis</a>  and the school teacher and writer 
	<a href="https://tefcrosmichaelidesen.wordpress.com/tag/mathematics///"> Tefcros Michaelides</a>  of the not-for-profit organization
	 <a href="http://thalesandfriends.org/"> Thales+Friends </a> (For the very active Greek site click  <a href="http://thalesandfriends.org/el/"> here</a>).
	Thales + Friends works to bridge the chasm between mathematics and other forms of cultural activity.
	To achieve its aims, Thales + Friends works to create opportunities for interdisciplinary research and communication, through lectures, discussions, publications, and reading groups.
	</p>
		<br><br>
	
	<ul>
		<li><a href="http://thalesandfriends.org/mykonos-conference/"> Mykonos conference</a>: Mathematics and narrative. 
			See the related article in <a href="http://link.springer.com/article/10.1007%2FBF02987152"> Nature </a> </li><br>
		<li><a href="http://thalesandfriends.org/delphi-conference/"> Delphi conference</a>: Circles Disturbed. 
			See the proceedings of the conference  in this <a href="http://press.princeton.edu/titles/9764.html"> book </a> edited by 
<a href="http://www.apostolosdoxiadis.com//"> Apostolos Doxiadis</a>
			and <a href="http://www.math.harvard.edu/~mazur/">Barry Mazur</a> </li><br>
	</ul>
	
	
</div>


 

</body>

</html>






Welcome to the **personal demo** of Academic. Other demos available include:

- [**Project Demo** (Academic's actual site)](https://sourcethemes.com/academic/)

**Over 100,000 [Amazing Websites](https://sourcethemes.com/academic/#expo) have Already Been Built with Academic**

**[Join](https://sourcethemes.com/academic/docs/install/) the Most Empowered Hugo Community**

{{% alert note %}}
This homepage section is an example of adding [elements](https://sourcethemes.com/academic/docs/writing-markdown-latex/) to the [*Blank* widget](https://sourcethemes.com/academic/docs/widgets/).

Backgrounds can be applied to any section. Here, the *background* option is set give an *image parallax* effect.
{{% /alert %}}
