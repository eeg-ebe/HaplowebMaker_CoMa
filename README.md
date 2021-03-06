# HaplowebMaker
HaplowebMaker is a web tool that takes as input one or several FASTA files and outputs for each of them one haploweb (Flot et al. 2010) based on either a minimum spanning or median-joining network (Bandelt, Forster & Röhl 1999).

# Installation

Just copy / paste this folder into a webserver.

If you want to use HaplowebMaker offline, either install a local webserver (recommended) or activate CORS requests so that the HaplowebMaker website can load its resources in the corresponding subdirectories (this is not recommended as it has some security implications).

In order to activate CORS requests in Firefox, enter about:config as URL, accept the warning message and set the setting "privacy.file_unique_origin" to false.

# Usage

Open http(s)://&lt;name of your webbrowser&gt;/&lt;directory&gt;/index.html in any modern browser that fully supports HTML 5.

# Reference
Bandelt, Forster & Röhl (1999) Median-joining networks for inferring intraspecific phylogenies. Molecular biology and evolution 16:37-48

Flot, Couloux & Tillier (2010) "Haplowebs as a graphical tool for delimiting species: a revival of Doyle's" field for recombination" approach and its application to the coral genus Pocillopora in Clipperton." BMC Evolutionary Biology 10:372

# For more information
Please refer to the [HaplowebMaker FAQ page](https://eeg-ebe.github.io/HaplowebMaker/faq.html)



