For an overview of the BDI pathogens group's work on sustainable containment of covid-19 please see <a href="https://045.medsci.ox.ac.uk/" target="_blank"> our website</a>.
This repository contains detailed reports and preprints.
The two preprints are now published in <a href="https://doi.org/10.1126/science.abb6936" target="_blank">*Science*</a>.

# <a href="https://github.com/BDI-pathogens/covid-19_instant_tracing/blob/master/Report%20-%20Effective%20Configurations%20of%20a%20Digital%20Contact%20Tracing%20App.pdf" target="_blank">Effective Configurations of a Digital Contact Tracing App: A report to NHSX</a>

<a href="https://www.linkedin.com/in/robert-hinch-16188511/?originalSubdomain=uk" target="_blank">Robert Hinch</a><sup>1</sup>,
<a href="https://www.linkedin.com/in/will-probert-82595827/?originalSubdomain=uk" target="_blank">Will Probert</a><sup>1</sup>,
<a href="https://scholar.google.com/citations?view_op=list_works&hl=en&authuser=1&user=YULTfcYAAAAJ" target="_blank">Anel Nurtay</a><sup>1</sup>,
<a href="https://michellekendall.github.io/" target="_blank">Michelle Kendall</a><sup>1</sup>,
<a href="https://www.bdi.ox.ac.uk/Team/c-wymant" target="_blank">Chris Wymant</a><sup>1</sup>,
<a href="https://www.bdi.ox.ac.uk/Team/matthew-hall" target="_blank">Matthew Hall</a><sup>1</sup>,
<a href="https://www.bdi.ox.ac.uk/Team/katrina-lythgoe" target="_blank">Katrina Lythgoe</a><sup>1</sup>,
<a href="https://github.com/abulascruz?language=jupyter+notebook&tab=stars" target="_blank">Ana Bulas Cruz</a><sup>1</sup>,
Lele Zhao<sup>1</sup>,
<a href="https://www.linkedin.com/in/andrea-stewart-64a15b1/" target="_blank">Andrea Stewart</a><sup>1</sup>,
<a href="https://www.ndph.ox.ac.uk/team/michael-parker" target="_blank">Michael Parker</a><sup>2</sup>
Ares Meroueh<sup>3</sup>,
Bryn Mathias<sup>3</sup>,
Scott Stevenson<sup>3</sup>,
Daniel Montero<sup>4</sup>,
James Warren<sup>4</sup>,
Nicole K Mather<sup>4</sup>,
Anthony Finkelstein<sup>5</sup>,
<a href="https://www.bdi.ox.ac.uk/Team/lucie-abeler-dorner" target="_blank">Lucie Abeler-Dörner</a><sup>1</sup>,
<a href="https://www.medawar.ox.ac.uk/team/david-bonsall" target="_blank">David Bonsall</a><sup>1</sup>
<a href="https://www.bdi.ox.ac.uk/Team/christophe-fraser" target="_blank">Christophe Fraser</a><sup>1</sup>

<sup>1</sup>
<a href="https://www.bdi.ox.ac.uk/" target="_blank">Big Data Institute</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK,
<sup>2</sup>
<a href="https://www.ethox.ox.ac.uk/Our-research/major-programmes/the-wellcome-centre-for-ethics-and-humanities" target="_blank">Wellcome Centre for Ethics and the Humanities and Ethox Centre</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK
<sup>3</sup>
<a href="https://faculty.ai/" target="_blank">faculty.ai</a>,
<sup>4</sup>
<a href="https://www.ibm.com/uk-en" target="_blank">IBM UK</a>,
<sup>5</sup>
<a href="https://www.turing.ac.uk/" target="_blank">UCL / Alan Turing Institute</a>,

The overarching objective of this report is to present simulations that will support the deployment and optimisation of digital contact tracing within an established programme of epidemic mitigation and control, and specifically to explore the conditions for success as countries prepare for exit from lockdowns. A lockdown can be regarded as a quarantine applied broadly to most of the population, excluding only key workers for example, whereas digital contact tracing can limit quarantine requests to those most at risk of transmitting the virus.

# <a href="https://github.com/BDI-pathogens/covid-19_instant_tracing/blob/master/Manuscript%20-%20Modelling%20instantaneous%20digital%20contact%20tracing.pdf" target="_blank">Quantifying dynamics of SARS-CoV-2 transmission suggests that epidemic control and avoidance is feasible through instantaneous digital contact tracing</a>

<a href="https://sites.google.com/site/lucaferretti/" target="_blank">Luca Ferretti</a><sup>1\*</sup>,
<a href="https://www.bdi.ox.ac.uk/Team/c-wymant" target="_blank">Chris Wymant</a><sup>1\*</sup>,
<a href="https://michellekendall.github.io/" target="_blank">Michelle Kendall</a><sup>1</sup>,
Lele Zhao<sup>1</sup>,
<a href="https://scholar.google.com/citations?view_op=list_works&hl=en&authuser=1&user=YULTfcYAAAAJ" target="_blank">Anel Nurtay</a><sup>1</sup>,
<a href="https://www.medawar.ox.ac.uk/team/david-bonsall" target="_blank">David Bonsall</a><sup>1,2</sup>
and
<a href="https://www.bdi.ox.ac.uk/Team/christophe-fraser" target="_blank">Christophe Fraser</a><sup>1,3†</sup>

<sup>\*</sup>contributed equally; <sup>†</sup> To whom correspondence should be addressed: christophe.fraser@bdi.ox.ac.uk

<sup>1</sup>
<a href="https://www.bdi.ox.ac.uk/" target="_blank">Big Data Institute</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK, <sup>2</sup>
<a href="https://www.ouh.nhs.uk/" target="_blank">Oxford University NHS Trust</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK, <sup>3</sup>
<a href="https://www.well.ox.ac.uk/" target="_blank">Wellcome Centre for Human Genetics</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK

### Abstract
Mobile phone apps implementing algorithmic contact tracing can speed up the process of tracing newly diagnosed individuals, spreading information instantaneously back through a past contact network to inform them that they are at risk of being infected, and thus allow them to take appropriate social distancing and testing measures. The aim of non-pharmaceutical infection prevention is to move a population towards herd protection, a state where a population maintains R<sub>0</sub> < 1, thus making it impossible for a pathogen to cause an epidemic. Here, we address epidemiological issues that affect the feasibility of an algorithmic approach to instantaneous contact tracing; ethical and implementation issues are addressed separately. First we quantify the parameters of COVID-19 in a framework that is consistent with the renewal equation formulation of epidemic spread. Second, we use an analytical solution to application of first-degree contact tracing in the renewal equation model to explore combinations of efficacy that can induce herd protection (R<sub>0</sub> < 1). With the emergence of the novel viral pathogen SARS-CoV-2, of clear
potential for a global pandemic with high fatality rates and incapacitated health systems, the question of prevention has critical priority. We come to the conclusion that isolating symptomatic cases and tracing their contacts in a classical manner is not sufficiently fast to stop the spread of the epidemic and needs to be accompanied by measures of social distancing that are disruptive to a wide number of people. We show that first-degree instantaneous contact tracing, informing users when they can move safely or when to seek medical help and avoid vulnerable individuals, has the potential to stop the spread of the epidemic if used by a sufficiently large number of people with reasonable fidelity.

# <a href="https://github.com/BDI-pathogens/covid-19_instant_tracing/blob/master/Policy%20forum%20-%20COVID-19%20containment%20by%20herd%20protection.pdf" target="_blank">Sustainable containment of COVID-19 using smartphones in China: Scientific and ethical underpinnings for implementation of similar approaches in other settings</a>

<a href="https://www.medawar.ox.ac.uk/team/david-bonsall" target="_blank">David Bonsall</a><sup>1,2</sup>
<a href="https://www.ndph.ox.ac.uk/team/michael-parker" target="_blank">Michael Parker</a><sup>3</sup>
and
<a href="https://www.bdi.ox.ac.uk/Team/christophe-fraser" target="_blank">Christophe Fraser</a><sup>1,4</sup>

<sup>1</sup>
<a href="https://www.bdi.ox.ac.uk/" target="_blank">Big Data Institute</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK,
<sup>2</sup>
<a href="https://www.ouh.nhs.uk/" target="_blank">Oxford University NHS Trust</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK,
<sup>3</sup>
<a href="https://www.ethox.ox.ac.uk/Our-research/major-programmes/the-wellcome-centre-for-ethics-and-humanities" target="_blank">Wellcome Centre for Ethics and the Humanities and Ethox Centre</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK,
<sup>4</sup>
<a href="https://www.well.ox.ac.uk/" target="_blank">Wellcome Centre for Human Genetics</a>,
<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a>,
UK

COVID-19 is a rapidly spreading infectious disease with pandemic potential, caused by the
novel virus, SARS-COV-2. With intensive care support, the case fatality rate is approximately
2%, and around half of infections become cases [1]. More concerning is that the fraction of
cases requiring intensive care support is 5%, and patient management is complicated by
requirements to use personal protective equipment (PPE) and engage in complex
decontamination procedures [2]. Fatality rates are likely to be higher in populations older
than in Hubei province (such as in Europe), and in low-income settings where critical care
facilities are lacking [3]. Even modest outbreaks will see fatality rates climb as hospital
capacity is overwhelmed, and the indirect effects caused by compromised health care
services have yet to be enumerated. Effective containment must be achieved.
