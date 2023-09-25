<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->


<h3 align="center">Analysis of long-term historical agroecology at the archaeological site of Dhiban, Jordan (ca. 1000 BCE - 1450 CE)</h3>

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

This repository contains the markdown and files needed to reproduce the analyses and visualizations found in [Farahani, A. 2018. A 2500-Year historical ecology of agricultural production under Empire in Dhiban, Jordan. Journal of Anthropological Archaeology 52: 137-155.](https://pdf.sciencedirectassets.com/272558/1-s2.0-S0278416518X0004X/1-s2.0-S0278416518300515/am.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFkaCXVzLWVhc3QtMSJIMEYCIQC2Xnrcx1VLx%2FgXD10gpYPjEsxGO549J1IgQQ7AX7kShwIhANJ0wLR68Ij8MTjfV4dsveZ1C9Imj2CLK3MZhIHu6udgKrMFCFIQBRoMMDU5MDAzNTQ2ODY1Igyzco%2FxJnHa4%2FJyd2kqkAUU5a%2BGsYnWtYcgvPaQ4LvQ4yQbkexBWh%2F0jHj3tLpUQN9NHRe%2FxLvBwbRiXRhyhNgYuKZO5ajN6jwq7mDO6JxS9jX1UewCUb9G7MwTxhHqNUhseAHndL2df3v0WAL4pSawj5WeGJoGKcbCbOiw%2F6e9ZO0A13jxpRJ5Tfg1Nvi%2Bd1gfrgKRR6%2FDhAhxLR4Updht0TdlbyKdBgVoItb%2Flkb2u0OBc%2ByL6zktDIRmNCK7PhADE%2B50QHWY320HJg%2Fst93sUCDqKSZCEBNuJF%2B95%2BA9rPg3LL7mhvsz9kmr1V3Gg04JNKRL%2BoU%2Fdj1lQSAnGUzQP8Q3shBGwDZ3Jwaj7X2EjJDelcdYJjZbd2JUZT0JZZ%2B0IsMb2fjcl%2Fh1FqYpZ1CVwvUA7w%2BDFzcY5jbkaVXcDeP4FakGN3ZqUPmDz7q0aiRIhM2sw13aVl1FAx1%2Fuu6qpVxZwm2h4J0kaOL9ouHyp2231bQ1PrgzIL4uGG31RMRyvRItWGGWRTXdqs8adsLkSg5NHCYmpop8q6VbGZN6RY4HABZmEXIfldWpHng9aDz%2FkWN5L0L%2FR1q1G2Yt1Nt5A6UnBoH0hdm4wDYFGjoJEH8W0OagZAtu%2FgNfOPW%2F72rf2lcsaXAHUNJ9ZEbeecwxq7%2FCF%2Bxgl22bs5fkbff6um9VjRGke32AKVnXDPakTAMQFvcioApgP84yU3K8YWckgidk6cPidC%2F06DozRtH8tIBsjTHlviN5fKggukzI91vlx%2Ba%2B6N6Iifh4YH5x%2BoVMdq6%2B3hiukFhXALJY0FOj2EC93kmJjAeFBE62CQ1bmR6ewjVqGiY0sQPTxLPQvm1LKCIf0KJQfFeqAuFUiocuHN2n5tL9%2Bkmb2zR8mR%2F9NzC6q8OoBjqwAdWxvTarQcJkI0Yxy3DnQO9qUUTddZTsG33cLtcB2v95qDVvz6psHcCDGdf7x0VT38%2B8kSgoR83TOFHNeVWLX2w%2FkR3iN7KzTrwiRcieKNACtGkfTcPFEcywqqLgNUQh101XFRMSuYeku5AVcB%2BaFnJ4f4pKiFStwVWo01ehmTx0rVnNLj31LMSjYiPAq%2B9Su0Osm6qQWOWIoMM0UbJYIbUmkIGytijPCfoIJC1YT2Fg&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230925T004522Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYSUR6AKC4%2F20230925%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a6f161210de8bd29595c2a9c618f9f9b0a5809c893f4e0366e095c82c72764f7&hash=81283dba0c76ca73f6fa2c787dafc58d2f3aa9cb3514b6feecf57a53dbe385a8&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0278416518300515&tid=pdf-797ec5c6-6161-441b-a345-f83554c6ebb8&sid=fd531bfa1b667540714a0e28ad4dab3d57a9gxrqa&type=client).

The goal of this research was to identify and understand how socio-political changes over nearly 2500 years at the [archaeological site of Dhiban](https://en.wikipedia.org/wiki/Dhiban,_Jordan) in the Hashemite Kingdom of Jordan affected, and were affected by, agricultural production.  Why agriculture?  Simply put, people must eat to survive.  And in empires, strategies of agricultural production often sit directly in-between the (coercive) power of state elites and the needs of local communities.  To investigate this relationship at Dhiban, I analyzed over 200 archaeological sediment samples to collect and identify archaeological plant remains: these are the actual physical residues (seeds, plant parts, etc.) of what crops these communities were growing and in what abundance.  The data reveal shifts in the abundances of particular crops correlating to separate moments of nonlocal imperial intervention at Dhiban, in particular a greater emphasis on grape production during the Byzantine (ca. 330–635 CE) period, and of wheat and barley during the Mamluk (ca. 1250–1450 CE) period.  I argued that these shifts were more likely a product of changes in socio-cultural priorities (more importance on sheep and goat husbandry in the Mamluk period) and economic necessities (greater local trade in the Byzantine period) in each of these time periods than due to climate change, although increasing aridity in the Mamluk period had some effect on the choices of farmers at Dhiban regarding what to grow.

See the compiled analyses and figures **<a href = "http://thebalkarchaeology.com/markdowns/dhiban_peb.html" target = "_new"> here</a>**.

For more about the archaeological site of Dhiban, see: 

- [Routledge, B., Fatkin, D.S., Porter, B.W., Adelsberger, K. and Wilson, A. 2013. Long-Term Settlement Change at Dhībān. Studies in the History and Archaeology of Jordan 11: 131-141 ](https://d1wqtxts1xzle7.cloudfront.net/34597797/Dhiban_Change_SHAJ-libre.pdf?1409611280=&response-content-disposition=inline%3B+filename%3DLong_Term_Settlement_Change_at_Dhiban.pdf&Expires=1695607204&Signature=FNQQdLMO7wEVkad-6mmqAn55-9RdjMRtty0BUf7F18Ht1VqBiXdaT7gy6mi132Yqf1ElAvkGQCxAA87x5p8sp9Vq-gvNKxJ85Y08OYpwSJGPLPmt8POf3TpKiO8AgnweGD6s-n2h9cQd5tB-ZVWaBq3dsVGs5DQ9DnYW7S0lxU0URsQF3wXvTgbN7JC1UVoP-tPjeZn-toHpeknwf1sdpgQ8D2sOb56aJP0B-j2gfVjGUK32UL5ycZHptjh72q6U4hBZjJ8k13UN5Gzzxvj0WE-pxlyzOxuFD5~uNU5C43U~LuG8ePtfpotkHxUL1HGC0RvptoyGyj1cJLmm-7yKHA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)

- [Fatkin, D.S., Adelsberger, K., Farahani, A., Fischer, A., Kansa, S.W., Lev-Tov, J., Morgan, C., Porter, B., Routledge, B. and Wilson, A. 2011. Digging deeper: Technical reports from the Dhiban Excavation and Development Project (2004-2009). Annual of the Department of Antiquities of Jordan 55:249-266.](https://escholarship.org/content/qt44m7f3mz/qt44m7f3mz.pdf)

- [Porter BW, Routledge BE, Simmons EM, Lev-Tov JS. 2014. Extensification in a Mediterranean semi-arid marginal zone: An archaeological case study from Early Iron Age Jordan's Eastern Karak Plateau. Journal of Arid Environments 104:132-48.](https://escholarship.org/content/qt1tt957q7/qt1tt957q7.pdf)

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
