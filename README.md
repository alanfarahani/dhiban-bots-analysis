<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->


<h3 align="center">Analysis and visualization of brachyuran crab isotopes from the archaeological site of KMA, central Jordan (ca. 1000 BCE)</h3>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#data-description">Data Description</a>
      <ul>
        <li><a href="#files">Files</a></li>
        <li><a href="#markdown">Markdown</a></li>
      </ul>
    </li>
    <li><a href="#prerequisites-and-use">Prerequisites and Use</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository contains the markdown and files needed to reproduce the analyses and visualizations found in [Farahani, A., Miller, M.J., Porter, B.W., Dawson, T. and Routledge, B. 2023. Stable isotopes of archaeological and modern semi-terrestrial crabs (Potamon potamios) provide paleoecological insights into brachyuran ecology and human resource acquisition in late Holocene Jordan. Quaternary International 658: 14-23](https://www.sciencedirect.com/science/article/pii/S1040618223000733).

In brief, our research sought to identify whether or not stable inorganic isotopes derived from crab carapaces recovered at the archaeological site of Khirbet al-Mudayna al-Aliya, located in south-central Jordan and dated to ca. 1000 BCE, could be used as hyper-local climate proxies.  The short answer is: no.  But the longer answer is: because of the behavioral ecology of these [specific semi-terrestrial freshwater crabs ](https://en.wikipedia.org/wiki/Potamon_potamios), stable inorganic oxygen and carbon isotopes give us insight into past brachyuran paleoecology and human resource acquisition, especially this past community's foraging behavior.

See the compiled analyses and figures **<a href = "http://thebalkarchaeology.com/markdowns/KMAcrabs.html" target = "_new"> here</a>**.

For more about the archaeological site of Khirbet al-Mudayna al-'Aliya (KMA), see: 

- [Farahani, A., Porter, B.W., Huynh, H. and Routledge, B. 2016. Crop storage and animal husbandry at early Iron Age Khirbat al-Mudayna al-‘Aliya (Jordan): a paleoethnobotanical approach (Vol. 69, pp. 27-89). American Schools of Oriental Research.](https://livrepository.liverpool.ac.uk/3002334/1/AASOR69-KMA.pdf)

- [Routledge, B. and Porter, B.,2016. A Place In-Between: Khirbat al-Mudayna al-‘Aliya in the Early Iron Age. In Crossing Jordan (pp. 323-329). Routledge.](https://www.taylorfrancis.com/chapters/edit/10.4324/9781315478579-44/place-bruce-routledge-benjamin-porter)

- [Porter BW, Routledge BE, Simmons EM, Lev-Tov JS. 2014. Extensification in a Mediterranean semi-arid marginal zone: An archaeological case study from Early Iron Age Jordan's Eastern Karak Plateau. Journal of Arid Environments 104:132-48.](https://escholarship.org/content/qt1tt957q7/qt1tt957q7.pdf)

- [Routledge, B. 2000. Seeing through walls: interpreting Iron Age I architecture at Khirbat al-Mudayna al-ʿAliya. Bulletin of the American Schools of Oriental Research, 319: 37-70.](https://www.journals.uchicago.edu/doi/abs/10.2307/1357559)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Data Description

There are two folders, one for data, and another for the Markdown.  See descriptions below:

### Files

- `KMA Potamon Archaeological Measurements and Isotopes.csv`
: The physical measurements of archaeological remains of brachyurans from KMA, including the stable inorganic isotope readings derived from those same remains conducted at UC Berkeley's [Center for Stable Isotope Biogeochemistry](https://nature.berkeley.edu/stableisotopelab/).

- `KMA Potamon Archaeological NISP.csv`
: The counts of the different archaeological brachyuran remains recovered at KMA by archaeological context.

- `KMA Potamon Modern Crab Locations.csv`
: The GPS coordinates of the sampled contemporary *Potamon potamios* specimens in the wadi system beneath KMA.

- `KMA Potamon Modern Measurements and Isotopes.csv`
: The physical measurements of all contemporary *Potamon potamios* specimens measured in the wadi system beneath KMA.  In addition, this file includes the stable inorganic isotope readings derived from sampled specimens (V<sub>PDB</sub>) and the water of the pools from which they were sampled (V<sub>SMOW</sub>).  These analyses were conducted at UC Berkeley's [Center for Stable Isotope Biogeochemistry](https://nature.berkeley.edu/stableisotopelab/).

- `KMA Potamon Modern Water Locations.csv `
: The GPS coordinates of the sampled pools that contained the *Potamon potamios* specimens in the wadi system beneath KMA.

### Markdown

- `Supplement.Rmd`
: An (R) Markdown that allows for interactive reproducibility of all of the figures and tables found in the manuscript, plus some additional analyses.

- `Supplement.html`
: A compiled version of the Markdown in the event you just wanted to <a href = "http://thebalkarchaeology.com/markdowns/KMAcrabs.html" target = "_new"> look at the analyses and figures </a>.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Prerequisites and Use

You will need:

- [Rstudio](https://posit.co/products/open-source/rstudio/)

- [R > v. 4.2.0](https://www.r-project.org/)

The packages needed for markdown compilation are listed at the beginning of the (R) markdown.

<!-- CONTRIBUTING -->
## Contributing

You can contribute to this repository by identifying coding errors, proposing more elegant syntax, or suggesting additional analyses / visualization. Any contributions you make are **very welcome**.

If you have a suggestion, first please open an issue with the tag "enhancement".  Depending on how much work you've already done, I might recommend that you fork the repo and create a pull request.

If so:

1. Fork the project

2. Create a branch (`git checkout -b enhancement/amazinganalysis`)

3. Commit your changes (`git commit -m 'Added an incredible new analysis'`)

4. Push to the branch (`git push origin enhancement/amazinganalysis`)

5. Open a pull request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Alan Farahani - alanfarahani@gmail.com

Project Link: [https://github.com/alanfarahani/KMA-crabs](https://github.com/alanfarahani/KMA-crabs)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [README template](https://github.com/othneildrew/Best-README-Template/tree/master)
* 🦀🦀🦀

<p align="right">(<a href="#readme-top">back to top</a>)</p>
