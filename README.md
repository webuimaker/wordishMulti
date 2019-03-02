This is the HUGO code for the https://worldish.se
This README file will contain instructions for each anticipated maintenance that we will do to the site.
### Contact form
To enable the form in the contact page and other , just type your Formspree email in the `config.toml` file.

```yaml
title: "worldish.se"
email = "your@email.com"
description: " description for site "
address: " Teknikringen 7, 583 30,<br>  LinkĂ¶ping, Sweden."
tel: " +46704-13 24 07"
baseurl: ""
url: " "
```
### SocialMedia
```
#socialMedia
fbUrl: "https://www.facebook.com/WorldishAB/"
fbIcon: "/images/fbfoot.jpg"
instagramUrl: "https://www.instagram.com/worldish_ab/"
instagramIcon: "/images/icon6.png"
youtubeUrl: " "
youtubeIcon: "/images/icon7.png"
twitterUrl: " "
twitterIcon: "/images/icon8.png"
linkedinUrl: "https://www.linkedin.com/company/worldish/"
linkedinIcon: "/images/linkedin.png"
```
### Language
```
defaultLang: en
languageNames:
  en: English
  se: Swedish
```
### Menu

You can also define the menu items that will appear in the top bar. Edit the `_data/menu.yml`  entries to create your menu.  Example Below:

```t:
  en:
    home:
      name: "Home"
      url: "/en/"
      
  se:
    hem:
      name: "Hem"
      url: "/se/"
```
The `en for English and se for Swedish ` parameter will determine the menu entries.

### Banner

You can also define the Banner text , image or video  that will appear in the top Banner. Edit the `_data/en/banner.yml` and `_data/se/banner.yml` entries to create your pages banner . Example Below:

```
banners:
 home:
    text: "Taking you across your language barriers"
    image: "/images/landing-photo-1.jpg/"
 team:
    text: "The Team"
    video: "/worldish-helen-v6final"
```
The `home  for Home page and team for team page ` parameter will determine the banner  entries.

### Helen Mission

You can also define the Helen Mission text and image  that will appear in the top Banner. Edit the `_data/en/helen-mission.yml` and `_data/se/helen-mission.ymll` entries to create your pages banner . Example Below:

```
title: "The Helen Mission"
desc: "<p>Through Helen, we foresee a world where language does not separate people. We aim to reach out to the healthcare community in Sweden and to the rest of the world wherever language barriers affect healthcare quality. We envision Helen as an innovative e-health solution for the future, empowering Healthcare professionals and patients globally.</p><p>Helen is currently being used in a variety of settings thoughtout Sweden and can be tailored to any human interaction service.</p>"
btnText: Read More
btnUrl: "#"
image: "/images/helentab2-shadow.png"
```


### Why Helen?

You can also define the Why Helen? text and image  that will appear in the top Banner. Edit the `_data/en/why-helen.yml` and `_data/se/why-helen.ymll` entries to create your pages Why Helen? . Example Below:

```
title: "Why Helen?"
fetures:
  - image: "/images/interaction.png"
    heading: "Improves Interaction"
    desc: "Healthcare staff and patients can communicate effectively using Helen’s accurate medical translations."
  - image: "/images/accessability.png"
    heading: "Faster Access"
    desc: "Helen helps patients communicate instantly with healthcare staff and receive care without delays."
  - image: "/images/reduced-costs.png"
    heading: "Reduces Cost"
    desc: "Helen’s digital capabilities saves time for healthcare staff and reduces patient-care process times."
btnText: Read More
btnUrl: "#"
```


### Why Helen?

You can also define the Why Helen? text and image  that will appear in the top Banner. Edit the `_data/en/why-helen.yml` and `_data/se/why-helen.ymll` entries to create your pages Why Helen? . Example Below:

```
title: "Why Helen?"
fetures:
  - image: "/images/interaction.png"
    heading: "Improves Interaction"
    desc: "Healthcare staff and patients can communicate effectively using Helen’s accurate medical translations."
  - image: "/images/accessability.png"
    heading: "Faster Access"
    desc: "Helen helps patients communicate instantly with healthcare staff and receive care without delays."
  - image: "/images/reduced-costs.png"
    heading: "Reduces Cost"
    desc: "Helen’s digital capabilities saves time for healthcare staff and reduces patient-care process times."
btnText: Read More
btnUrl: "#"
```

### Cases

You can also define the Cases text and image  that will appear in the top Banner. Edit the `_data/en/cases.yml` and `_data/se/cases.ymll` entries to create your pages Why Helen? . Example Below:

```
title: "Cases"
fetures:
  - image: "/images/cases/labour-ward.jpg"
    heading: "Labour Ward"
    desc: "Pregnant mothers face even more challenges, due to language barriers, than anyone else. Our research shows that, a lot of the women coming to maternity wards decline the use of interpreters as they find it very compromising of their integrity having to talk to your doctor or midwife through a stranger. They feel their privacy compromises in such situations. There is a huge gender aspect also when it comes to women's health. Helen has proved to be a problem solution here."
    btnText: "Read More"
    btnUrl: "#"
```


### Testimonials

You can also define the Testimonials text and image  that will appear in the top Banner. Edit the `_data/en/Testimonials.yml` and `_data/se/Testimonials.ymll` entries to create your pages Why Helen? . Example Below:

```
title: "Testimonials"
desc: "Don't take our word. See our testimonials"
testimonials:
  - image: "/images/testimonial/testimonial-1.png"
    comments: "We have reduced our usage of Arabic translators to 30%"
    logo: 
    commentsBy: "Delivery Ward - Linköping University Hospital, Sweden"
```

### Book Demo

You can also define the Book Demo text and image  that will appear in the top Banner. Edit the `_data/en/bookdemo.yml` and `_data/se/bookdemo.ymll` entries to create your pages Why Helen? . Example Below:

```
title: "Want to meet Helen?"
desc: 
btn: "/images/bookdemo.png"
btnUrl: "#"
name: "Name"
role: "Role"
organization: "Organization"
telephone: "Telephone"
email: "Email"
```

### In Media

You can also define the In Media text and image  that will appear in the top Banner. Edit the `_data/en/media.yml` and `_data/se/media.yml` entries to create your pages In Media . Example Below:

```
title: "In Media"
desc: "Articles that Worldish has been featured in"
medias:
  - image: "/images/inMedia/1.jpg"
    title: "De fick avtalet med sjukvården"
    comments: "LINKÖPING Fem vårdcentraler och kliniker i regionen får nu ett nytt digitalt verktyg för att överbrygga språkbarriärer mellan patient och läkare. "
    logo: "/images/inMedia/corren-logo.png"
    commentsBy: 
    url: "https://www.corren.se/nyheter/de-fick-avtalet-med-sjukvarden-om5547361.aspx" 
  - image: "/images/inMedia/2.jpg"
    comments: "Medicinska tolkningsappar förenklar kommunikationen mellan patienter som talar andra språk och vårdgivare. "
    logo: "/images/inMedia/dm-logo.png"
    commentsBy: 
    url: "https://www.dagensmedicin.se/artiklar/2017/10/20/tolkande-appar-rader-bot-pa-sprakbarriarer/" 
```

### Awards and Appreciation

You can also define the Awards and Appreciation image  that will appear in the top Banner. Edit the `_data/en/award.yml` and `_data/se/award.yml` entries to create your pages In Media . Example Below:

```
title: "Awards and Appreciation"
awards:
  - image: "/images/awards/bravest-Company-2018.jpg"
  - image: "/images/awards/prins-daniel_s-fellowship-2018.jpg"
  - image: "/images/awards/Swedbank-Rivstart-2017.jpg"
```


### The Team

You can also define the The Team text and image  that will appear in the top Banner. Edit the `_data/en/team.yml` and `_data/se/team.yml` entries to create your pages In Media . Example Below:

```
title: "The Team "
desc: "We are a team evolved from the academia of Linköping University, Sweden. We are an international and multicultural team with competences in the fields of Software engineering, Language technology, Cognitive science, Business administration, Innovation management and Medicine."
btnText: "Meet The Team"
btnUrl: "/en/team/"
advisorsTitle: "Medical Advisory Board"
advisorsDesc: "We are a team evolved from the academia of Linkoping University, Sweden."
technologyAdvisorsTitle: "Technology Advisory Board"
technologyAdvisorsDesc: "We are a team evolved from the academia of Linkoping University, Sweden."
teams:
  - image: "/images/teams/abhishek-squar.jpg"
    name: "Abhishek Jacob Chethikatt"
    pos: "Co-founder & CEO"
    email: "abhishek.jacob2worldish.se"
    phone: "46704132407"
    social:
      - icon: "/images/linkedin-icon.png"
        link: "https://www.linkedin.com/in/abhishekjacobc/"
      - icon: "/images/twit-icon.png"
        link: 
      - icon: "/images/fbicon.png"
        link: 
  - image: "/images/teams/naveen-square.jpg"
    name: "Naveen Sasidharan"
    pos: "Co-founder & COO"
    email: "naveen@worldish.se"
    phone: "46704-13 24 07"
    social:
      - icon: "/images/linkedin-icon.png"
        link: "https://www.linkedin.com/in/naveensasidharan/"
      - icon: "/images/twit-icon.png"
        link:  
      - icon: "/images/fbicon.png"
        link:
```

### Partners

You can also define the Partners image  that will appear in the top Banner. Edit the `_data/en/partners.yml` and `_data/se/partners.yml` entries to create your pages partners . Example Below:

```
title: "Partners"
desc: "Don't take our word. See our testimonials"
media:
  - image: "/images/partners/almi-logo.png"
    url: "abc.com"
  - image: "/images/partners/lead.jpg"
    url: "abc.com"
  - image: "/images/partners/liU.png"
    url: "abc.com"
  - image: "/images/partners/liuinnovation-crop.jpg"
    url: "abc.com"
  - image: "/images/partners/NFC_Ydre_Linkoi.png"
    url: "abc.com"
  - image: "/images/partners/regionostergotland-logo.png"
    url: "abc.com"
```


### Have any queries

You can also define the Have any queries image/text  that will appear in the top Banner. Edit the `_data/en/queries-form.yml` and `_data/se/queries-form.yml` entries to create your pages Have any queries . Example Below:

```
title: "Have any queries"
desc: "Send us your message"
feilds:
  - placeholder: "Your name"
    type: "text"
    required: "true"
  - placeholder: "Your e-mail"
    type: "email"
    required: "true"
  - placeholder: "Subject"
    type: "text"
    required: "true"
textArea: "Message"
btnText: "Send a message"
```
### Footer

You can also define the footer image/text  that will appear in the top Banner. Edit the `_data/en/footer.yml` and `_data/se/footer.yml` entries to create your pages footer . Example Below:

```
info: "Through Helen, we foresee a world where language does not separate people. We aim to reach out to the healthcare community in Sweden and to the rest of the world wherever language barriers affect healthcare quality."
getInTouchText: "Get In touch"
getInTouchUrl: "#"
getDirectionText: "Get directions"
getDirectionUrl: "#"
```

