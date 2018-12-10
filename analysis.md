---
title: Analysis
layout: blocks
date: 2018-12-07 06:25:21 +0000
page_sections:
- template: navigation-header
  block: header-1
  logo: "/uploads/2018/12/07/eye_icon_nounproject_qolbinsalim.png"
  navigation:
  - link: timeline
    link_text: TIMELINE
  - link: analysis
    link_text: ANALYSIS AND VISUALIZATIONS
  - link: nextsteps
    link_text: NEXT STEPS
  - link: about
    link_text: ABOUT US
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/12/09/Screen Shot 2018-12-09 at 12.34.16 AM.png"
  caption: "<!--\tExported from Voyant Tools (voyant-tools.org). The iframe src attribute
    below uses a relative protocol to better function with both http and https sites,
    but if you're embedding this into a local web page (file protocol) you should
    add an explicit protocol (https if you're using voyant-tools.org, otherwise it
    depends on this server. Feel free to change the height and width values or other
    styling below: --> <iframe style='width: 1057px; height: 533px;' src='//voyant-tools.org/tool/Loom/?corpus=df672285c836b1fef0d52e3eec1beb01'></iframe>"
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Voyant: Distance Reading, Up-Close</strong>"
  content: 'Our two Voyant visualizations are the result of ingesting the  .txt  files
    from 30 full-text treaties between the United States and  various  indigenous
    peoples in the 18th and 19th centuries. The first   visualization is called Loom
    and graphs the instances of 500 of the most   common words present across the
    text. Though visually engaging and   dynamic when you start to drag your cursor
    across the left-hand list of   words, this visualization does not provide enough
    information about the   documents at first glance. If you play around with the
    settings and   lower the word count, then you begin to see interesting word occurrences   throughout
    the available menu categories. <br><br>The second   visualization, Dreamscape,
    is an experimental tool from Voyant that   highlights geographic text in your
    files and maps it. Here we begin to   see a pattern emerge. All of the locations
    highlighted are in the   eastern region of the land in question. Closer reading
    of the text   reveals that many of the later treaties involve areas further west
    so,   though this image is very dynamic, it is just the first step of many   necessary
    to begin a large-scale, investigative digital humanities   project.<br><br>Voyant
    offered us a useful way to begin looking more   closely at the text. Through distance
    reading, we were able to pull out   what kinds of information we wanted to look
    for in the next phases of   our analysis: geographical maps and network analysis. '
  media:
    image: "/uploads/2018/12/10/Screen Shot 2018-12-09 at 11.57.23 PM.png"
    alt_text: 'A list of blue and black text revealing a screenshot of our textual
      corpus in Voyant, an open-source analysis software. '
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/12/09/Screen Shot 2018-12-09 at 12.34.16 AM.png"
  caption: "<!--\tExported from Voyant Tools (voyant-tools.org). The iframe src attribute
    below uses a relative protocol to better function with both http and https sites,
    but if you're embedding this into a local web page (file protocol) you should
    add an explicit protocol (https if you're using voyant-tools.org, otherwise it
    depends on this server. Feel free to change the height and width values or other
    styling below: --> <iframe style='width: 1057px; height: 533px;' src='//voyant-tools.org/tool/DreamScape/?corpus=df672285c836b1fef0d52e3eec1beb01'></iframe>"
- template: content-feature
  block: feature-1
  media_alignment: Right
  media:
    image: "/uploads/2018/12/09/Screen Shot 2018-12-08 at 10.36.11 PM.png"
  headline: "<strong>Palladio: Visualizing Signatory Networks in Treaty Text</strong>"
  content: 'To understand whether or not the treaties within our sample data set were
    connected, we elected to design a data model well suited for network visualization.
    The images to the right of this description and below are all screenshots of our
    data visualized in Palladio. Of the seven treaties analyzed through this web-based
    software, four of them had connections with one another. <br><br>The two treaties
    from 1865 (Treaty with the Apache, Cheyenne and Arapaho, Treaty with the Cheyenne
    and Arapaho) have a total of 20 common signatories. This isn''t much of a surprise
    as two of the three tribes across the two documents are the same, so there was
    a high-likelihood that we''d find connections between them from the outset. Somewhat
    more surprisingly, the Treaty with the Wyandot (1785) and the Treaty with the
    Six Nations (1784) have five signatories in common. Each of the common signatories
    belongs to a representative of the United States government. This means that elected
    officials and government employees of the era commonly worked with multiple tribes
    and indigenous nations to construct treaty documents and redefine where the United
    States began and ended. <br><br>Future instantiations of this project would benefit
    from a broader data set. Imagine what connections might exist if we were able
    to build a network analysis of 200 or 300 treaties? What would that reveal about
    the relationships and rights present within them? <br><br>Even further, how could
    these networks be visualized if we paired this information with the accompanying
    geocoordinates where each treaty was signed? Would we learn new things about how
    these treaties impacted cartography or how cartography impacted the treaties? '
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/12/09/netviz_one.png"
  caption: Treaty with the Apache, Cheyenne and Arapaho; Treaty with the Cheyenne
    and Arapaho, both 1865
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/12/09/Screen Shot 2018-12-08 at 10.47.27 PM.png"
  caption: Treaty with the Wyandot, 1785; Treaty with the Six Nations, 1784
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/2018/12/10/1852_resized.png"
    caption: Treaty with the Apache, 1852
  image_2:
    image: "/uploads/2018/12/10/1778_resized.png"
    caption: 'Treaty with the Delaware, 1778 '
- template: full-width-media-element
  block: media-1
  caption: Treaty with the Comanche, Kiowa and Apache, 1853
  image: "/uploads/2018/12/09/Screen Shot 2018-12-08 at 10.40.31 PM.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Map Warper and Google Earth: Comparative Visual Analysis of Geographic
    Representations</strong>"
  content: Using New York Public Library's Map Warper interface, historic maps were
    "rectified" with current geo-spatial data. These rectified maps were then exported
    into a shared Google Earth Pro folder. Transparency sliders allow users to seamlessly
    alternate between visual representations of the "same" physical space. How did
    the shape and character of the land evolve over time in these representations?
    How does the edge of the map effect the way we perceive space?<br><br>These images
    document the working prototype for this visualization. Due to limitations in Google
    Earth interoperability, these visualizations are currently inaccessible through
    the web.
  media:
    image: "/uploads/2018/12/09/MAP_WARPER_animation.gif"
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/2018/12/09/GoogleEarth1.jpg"
    caption: 'Warped Maps Layered in Google Earth '
  image_2:
    image: "/uploads/2018/12/09/GoogleEarth2.jpg"
    caption: Warped Map as .kml layer in Google Earth
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/2018/12/09/vlcsnap-2018-12-09-09h17m57s554.png"
  image_2:
    image: "/uploads/2018/12/09/vlcsnap-2018-12-09-09h17m21s245.png"
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/2018/12/09/movie8-000281.jpg"
  image_2:
    image: "/uploads/2018/12/09/Capture1.JPG"
- template: content-feature
  block: feature-1
  media_alignment: Right
  media:
    image: "/uploads/2018/12/10/date v hue.jpg"
  headline: "<strong>ImagePlot Visualizations: Image Collection Analysis</strong>"
  content: 'These visualizations employ computer vision and digital image analysis
    techniques to analyze our collection of maps. Building off of work by <a href="http://lab.softwarestudies.com/p/overview-slides-and-video-articles-why.html#1"
    title="">Lev Manovich</a> and the <a href="http://lab.culturalanalytics.info/p/projects.html"
    title="">Cultural Analytics Lab</a>,  we investigate how digital tools may help
    us explore patterns in a visual collection. Manovich defines Cultural Analytics
    as "<strong>the analysis of massive cultural data sets and flows using computational
    and visualization techniques,"</strong> and while our data sets are not quite
    "massive," this experiment demonstrates the viability of applying visual analysis
    to a set of map images. <br><br>Using <a href="http://lab.softwarestudies.com/p/software-for-digital-humanities.html"
    title="">a suite of open source software</a> tools developed by the Cultural Analytics
    Lab, we were able to analyze visual qualities (hue, saturation, brightness, shape,
    and size) of our map images en mass. When combined with our already rich metadata
    on these digital objects, this new data allowed us to create original visualizations
    to explore the visual qualities of the collection.  <br> <br>The small size and
    scope of our image collection severely limits the analytic value of these tools,
    but with the hundreds of thousands of historic cartographic images freely available
    through the web, we believe these techniques could be meaningfully applied to
    similar image collections of much larger scale. Moreover, by integrating geolocation
    data into the image metadata, these tools could offer new pathways into understanding
    the way space and geography have been depicted over time. As computer vision continues
    to improve identifying features such as shape, line patterns and even text, these
    new capabilities could be meaningfully applied as well. <br><br>These visualizations
    pose the following questions: what can quantitative analysis of visual qualities
    like color, hue, saturation and shape tell us about mapping, and how can we meaningfully
    analyze massive collections of historic maps using digital tools? Finally, we
    must recognize that because these images are "digital surrogates" of the original
    paper maps, discrepancies in digitization standards could greatly effect results.
    For this collection, all digital images share the same source (<a href="https://digitalcollections.nypl.org/"
    title="">NYPL Digital Collections</a>) and digitization standards.  '
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/2018/12/09/measurementsMAIN.txt - saturation_median vs hue_median.jpg"
    caption: Median Saturation vs. Median Hue
  image_2:
    image: "/uploads/2018/12/09/measurementsMAIN.txt - date vs hue_stdev.jpg"
    caption: 'x-axis: date Issued; y-axis: hue '
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/2018/12/10/date v hue.jpg"
    caption: 'x-axis: date issued; y-axis hue-standard deviation'
- template: detail-content
  block: text-1
  content: '<p>____________________________________________________________________</p><h5>This
    project was developed in a graduate information studies course at UCLA in the
    fall of 2018.<br><br>Imperial Eyes acknowledges the Tongva peoples as the traditional
    land caretakers of <a href="https://www.aisc.ucla.edu/sounds/world.wav">Tovaangar</a>
    (Los Angeles basin, So. Channel Islands) and are grateful to have the opportunity
    to work for the <a href="https://www.aisc.ucla.edu/sounds/people.wav">taraaxatom</a>
    (indigenous peoples) in this place. As a land grant institution, we pay our respects
    to <a href="https://www.aisc.ucla.edu/sounds/ancestors.wav">Honuukvetam</a> (Ancestors),
    <a href="https://www.aisc.ucla.edu/sounds/wise%20people.wav">Ahiihirom </a>(Elders),
    and <a href="https://www.aisc.ucla.edu/sounds/our%20relatives.wav">eyoohiinkem</a>
    (our relatives/relations) past, present and emerging." <br><br>This territory
    acknowledgement and accompanying pronunciations are attributed to <a href="https://www.wacd.ucla.edu/"
    title="">the UCLA World Arts and Cultures/Dance Department</a>.</h5><p><a href="https://creativecommons.org/licenses/by-nc/4.0/"
    title=""><img src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative
    Commons License with three cirular images: the first image depicts two c''s to
    mean Creative Commons, the second is the figure of a human to request attribution,
    and the third is of a dollar sign with a slash through it to demonstrate that
    this is a non-commercial project."></a></p>'
menu:
  main:
    weight: 3
    title: Analysis and Visualizations

---
