# Welcome

summarise these:

* [HS2 case study](https://medium.com/@swardley/from-hs2-to-china-and-back-again-6bce5764ea14)
* [tweet thread](https://threadreaderapp.com/thread/1068822023126827010.html)
* [Pioneers, Town Planners and those missing Settlers](https://blog.gardeviance.org/2011/02/pioneers-town-planners-and-those.html?m=1)
* [What do Wardley maps really map? A settler writes](https://blog.mattedgar.com/2017/08/13/what-do-wardley-maps-really-map-a-settler-writes/)
	* The use of the term “evolution” bothers me. It carries strong implication of an inevitable unidirectional process. Only with the benefit of hindsight can evolution be said to be a straight line, and that’s just a trick of perspective.
	* [All maps are socially constructed](https://en.wikipedia.org/wiki/Social_construction_of_technology). Wardley maps are therefore an artefact of social science, not (despite the Darwinian metaphor) a life science. The x-axis shows not evolution but level of consensus.

This is an edited and abridged version of Simon Wardley's "Wardley Maps" ascii doc. It's a [fork of andrewharmellaw/wardley-maps-book](https://github.com/andrewharmellaw/wardley-maps-book)  simply takes all his [medium posts](https://medium.com/wardleymaps) and joins them together for ease of reading.  

# Who I am and why I am doing this

My background is as an interdisciplinary researcher working at the interfaces of geo-science, heritage, smart-cities, remote sensing, plant and soil science, computing and knowledge engineering. I have undertaken research in a number of contrasting departments (humanities, social science and science) and am committed to approaches that maximize academic, industry, policy and public impact. This is demonstrated by engagement with community and policy groups, presentations at public science and industry events and providing timely access to research outputs under licenses that encourage re-use and participation. I have a particular interest in evidence-based approaches employing open data and am an advocate of open science. Open science approaches have the potential to dramatically increase impact beyond the traditional communities of discourse.

I have a long standing obsession with data quality. I also believe that the current focus on *Open Data* is an appropriate vehicle to drive improvements in data quality. The McKinsey Global Institute report [-@mckinsey_open_2013] which examined the economic impact of Open Data came to similar conclusions: whilst estimating that globally open data could be worth a minimum of $3 trillion annually there is a recognition that there are some challenges and opportunities particularly in terms of skills and quality.


Open data will not reach its full potential without careful choices about how to aggregate, present, and enable interaction with it [@goldstein_beyond_2013 p. 151]. @fry_computational_2004 describes this as a seven stage process: acquire, parse, filter, mine, represent, refine, and interact. The average consumer (individual, business or organization) will be dependent on others for six of those seven steps after data is released. 

Since 2014 I have been working in industry.

I'm attempting to reframe Simon Wardley's approach in two broad ways:

1. Many of Simon's examples are embedded in software development, yet the "Wardley Maps" rationale is based on a purely business need. I feel the software driven metaphor dilutes the impact of the approach.  
2. I think the approach is a way of faceting the multidimensional nature of businesses (most notably in terms of knowledge and maturity). I want to expand on this and generalize it.  


The issue surrounding the *commodity* products described by Simon is that they are all defined by IT. I think this is an ongoing issue with IT - IT seems to want to be the focus of the solution and in doing so it has beome part of the problem. I see this in *agile*. Agile has its roots in [W. Edwards Deming](http://en.wikipedia.org/wiki/W._Edwards_Deming). Deming was a statistician credited with providing the leadership that led to the post-war economic turn-around of Japan. His focus was on quality within the production process which ultimately led to exemplar implementations like the [*Toyota Production System*](http://en.wikipedia.org/wiki/Toyota_Production_System), which in turn inspired [Lean manufacturing](http://en.wikipedia.org/wiki/Lean_manufacturing) leading to [Lean software development](http://en.wikipedia.org/wiki/Lean_software_development) employing [Agile methods](http://en.wikipedia.org/wiki/Agile_software_development). Ironically, benefits in software production are being used to argue for changes in business practice. I'm not sure one size fits all - why would one simply copy a technique that worked in software engineering and assume it works across all businesses.

However, the evolution of products and services is something that is more generic. Commodity products, as described by Simon, represent the peak of evolution. They are well understood systems and processes whose workings are completely abstracted from those that re-use the commodity or service. Commodity products require underlying profundity of understanding and efficiency of process. However, that is not the real benefit of a commodity product. A commodity product facilitates change and innovation. New things can be built, innovation can be driven.  

I want to get closer to this essence.


# Downloads
If you want the PDF, or MOBI versions of this book, click on the "releases" tab above.

# Generating the book yourself
All these generators require you to have installed [asciidoctor](https://asciidoctor.org/docs/user-manual/). Then select the command you require to generate the output you desire.

## HTML
To generate the HTML version of this book, run the following command in the base directory of this repository:

    asciidoctor wardley-contextual-landscapes.adoc

## PDF
To generate the PDF version of this book, you additionally need to install [asciidoctor-pdf](https://asciidoctor.cn/docs/convert-asciidoc-to-pdf/) with the following command:

    gem install --pre asciidoctor-pdf

Then you can run the following command in the base directory of this repository:

    cd /home/beckant/git_shares/OtherRepositories/wardley-landscapes; asciidoctor-pdf wardley-contextual-landscapes.adoc

## .MOBI (Kindle)
To generate the .mobi version of this book you additionally need to install [Asciidoctor-EPUB3](https://asciidoctor.org/docs/asciidoctor-epub3/) and [kindlegen](https://rubygems.org/gems/kindlegen/versions/3.0.3) both via  Ruby gems - the instructions are in the linked pages.  The pre-requisite to run both of these is Ruby. You can then run the following command in the base directory of this repository:

    asciidoctor-epub3 -a ebook-format=kf8 wardley-maps-book.adoc

# Contributing
Contributions are cool, and also very welcome.  There is a [code of conduct](CODE_OF_CONDUCT.md), and a [contribution guide](CONTRIBUTING.md) which you can familiarise yourself with if you want to get involved (even if its just fixing a typo).  They should be _very_ unsurprising to anyone used to the OSS world.

# To Do
