

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ChrifaBahrouni/Google-Plays-Stors-Apps-Data/main?labpath=notebook.ipynb)
# Google-Plays-Stors-Apps-Data
## Data Dictionary






<section id="title-slide">
<table class="kms" border="0"  width="100%"  style="width:100%;text-align:center;">
  <tr>
    <td width="99%" align="center" ><p class="fragment fade-down" data-fragment-index="3"><img src="images/images.png" width="350" height="350" style="border-radius: 10px"></p></td>
    <td width="99%" align="center"><p class="fragment fade-up" data-fragment-index="3"><img src="images/isg.jpeg" width="350" height="350" style="border-radius: 10px"></p></td> 
    <td width="99%" align="center"><p class="fragment fade-down" data-fragment-index="3"><img src="images/epidgt.jpg" width="350" height="350" style="border-radius: 10px"></p></td>
  </tr>
</table>
    <br><h1><i><p class="fragment" data-fragment-index="1">Google Play Store apps and reviews</p></i></h1>
    <h4><i><p class="fragment" data-fragment-index="1">cycle ingenierie en genié logiciel : Analyse de données </p></i></h4>
    <br><br><br><br><br><br>
   <div class="uu_title_container">
        <smaller>
        <div class='column'><p class="fragment" data-fragment-index="2">
            <b>Presented by:</b><br>Chrifa Bahrouni 
            </p></div>  
           <div class='column'></div> 
       </smaller>
    </div>
</section> 


# Présentation du projet 
###  Google Play Store apps and reviews
<p>Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.</p>
<p><img class="logo" src="https://assets.datacamp.com/production/project_619/img/google_play_store.png" alt="Google Play logo"></p>


**data_apps.csv**

| variable       | class     | description                                                                  |
|:---------------|:----------|:-----------------------------------------------------------------------------|
| App            | character | The application name                                                         |
| Category       | character | The category the app belongs to                                              |
| Rating         | numeric   | Overall user rating of the app                                               |
| Reviews        | numeric   | Number of user reviews for the app                                           |
| Size           | character | The size of the app                                                          |
| Installs       | character | Number of user installs for the app                                          |
| Type           | character | Either "Paid" or "Free"                                                      |
| Price          | character | Price of the app                                                             |
| Content Rating | character | The age group the app is targeted at - "Children" / "Mature 21+" / "Adult"   |
| Genres         | character | Possibly multiple genres the app belongs to                                  |
| Last Updated   | character | The date the app was last updated                                            |
| Current Ver    | character | The current version of the app                                               |
| Android Ver    | character | The Android version needed for this app                                      |

**data_reviews.csv**

| variable               | class        | description                                           |
|:-----------------------|:-------------|:------------------------------------------------------|
| App                    | character    | The application name                                  |
| Translated_Review      | character    | User review (translated to English)                   |
| Sentiment              | character    | The sentiment of the user - Positive/Negative/Neutral |
| Sentiment_Polarity     | character    | The sentiment polarity score                          |
| Sentiment_Subjectivity | character    | The sentiment subjectivity score                      |

