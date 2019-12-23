+++
# Project title.
title = "Gagnvirk reiknivél fyrir tekjuskattsbreytingar"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "Lítil reiknivél sem sló í gegn á netinu"

# Tags: can be used for filtering projects.
# Example: `tags = ["Shiny""]`
tags = ["Shiny"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/hlynur"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Waterfall plott fyrir tekjuskattsbreytingar"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Stóra verkefnið í vinnu minni hjá Fjármála- og efnahagsráðuneytinu hefur verið þróun á örhermilíkani fyrir tekjuskatts- og bótakerfi einstaklinga á Íslandi. Raunar hófst verkefnið fyrstu vikuna mína í starfi, Nóvember 2016. Þegar fram liðu stundir lét heldur betur reyna á þá vinnu þegar stjórnvöld fóru að skoða gagngera endurskoðun tekjuskatts- og bótakerfa einstaklinga. Ég hef verið svo lánsamur að taka þátt í þeirri vinnu ýmist sem nefndarmaður eða starfsmaður nefnda og þróun líkansins og fór í annan gír í ljósi mikilvægi þeirrar vinnu. 

En þegar nýtt tekjuskattskerfi lá fyrir voru breytingarnar á þann veg að ekki allir skildu hvað fælist í þeim. Það er viðbúið, enda er tekjuskattskerfið alls ekki einfalt. Á þeim tíma hafði Stjórnarráðið ekki [Shinyapps](http://shinyapps.io) aðgang (sem það gerir í dag), en ég sá fyrir mér að [Shiny](https://shiny.rstudio.com/) væri hið fullkomna tól til að miðla þessum breytingum til skattgreiðenda á gagnvirkan hátt. Þannig ég tók mig til í mínum eigin frítíma og ákvað að setja upp reiknivél sem sýndi fólki, bæði myndrænt og í beinhörðum krónutölum, hver áhrifin á það væru, eftir völdum tekjum. 

Ég sá fyrir mér að svokallað 'Waterfall plot' gæti komið upplýsingunum til skila á þægilegan hátt. Það er þó svo að það er ekki innbyggt "geom" fyrir waterfall plott í [ggplot2](https://ggplot2.tidyverse.org/) þannig að það varð skemmtilegt hliðarverkefni að láta það ganga upp (sem reyndist auðvitað ekki mikið mál, frekar en annað þegar kemur að hinum frábæra ggplot2 pakka). 

### Viðbrögðin 
Þessi nálgun sló í gegn, svo lítið eitt sé sagt. Innan skamms voru allir helstu fréttamiðlar búnir að fjalla um málið og vísa á reiknivélina, andlitið mitt var orðið forsíðumynd á [Vísir.is](http://www.visir.is) og ég búinn að fara í útvarpsviðtal og ég veit ekki hvað og hvað. Umferðin inn á vefinn var svo mikil að ég pungaði út 30þúsund kalli til að reyna að tryggja að það væru nógu margir instansar virkir til að halda reiknivélinni gangandi. Heimasíminn hjá mér stoppaði ekki, í orðsins fyllstu, í tvo sólarhringa - þannig á endanum þurfti ég bara að taka hann úr sambandi. 

Þannig heilt yfir var þetta bara frábært og fyndið og merkileg upplifun. Nú hef ég allavegana prófað að verða 'viral'.

## [Hér getur þú skoðað reiknivélina](https://hlynur.shinyapps.io/tekjuskattskerfi) 