# Advertising Technology

## Advertising types

Display, Branded, Targeted, Programmatic

### Branding ads

Branding ads are large, sweeping, image-based messages designed to increase familiarity with a brand and associate a product with a set of values.

Branding campaigns are historically associated with television

### Display ads

Display ads are rectangular ads that come in several standard formats based on their shape. Names are based on the longest edge and the width to height ratio. Examples include: Horizontal 2:1 and Vertical 1:2. Standards are set by the Interactive Advertising Bureau or IAB.

Advertising is shifting from Display/Branding ads to Targeted ads focused on driving transactions.

### Targeted ads

Targeted ads are designed to be as compelling as possible to a particular person or group of people.

#### How targeted ads work

Websites gather information about you from your browser and from tracking cookies. Tracking cookies report your browsing and purchase histories back to the advertising platform.

Websites aggregate all this information into two buckets: 

1. behavioral data they have on what kinds of sites you’ve looked at, how much time you’ve spent on them, and whether you bought anything, and 
2. demographic information that they’ve estimated based on these online behaviors, such as your age, educational level, family status, income bracket, and interests. 

This information is then used to tailor ads to users along two different parameters: 1) **what you do (i.e., behavioral targeting** and **2) who you are (i.e., demographic targeting).**

Data collection can also happen on hardware. One example of hardware-based data collection takes place on Google’s Android phones and operating systems. 

This information is not only useful for targeting ads directly to you, but also for targeting ads to people like you. Websites aggregate user data to build a snapshot of their visitors’ demographics, including average age range, ethnicity, where users live and work, income, and educational level. This user data, called “inventory,” is then used to sell ad space to brands and advertisers via ad agencies.

#### How ads are bought and sold

The industry metric for buying inventory is the “impression.” Impressions are sold in CPM, or “cost per thousand views,” The “M” comes from “mille,” the Latin word for “thousand.” Advertisers typically set their impressions targets and spending limits together: “We want to reach [Y] number of impressions, and we will spend [X] amount for them.”

Publishers can offer alternative pricing models based on other viewer actions (outside of just impressions), such as CPC, Cost Per Click (when a viewer clicks on an ad), or CPA, Cost Per Action (when a viewer both clicks and makes a purchase).

### Programmatic ads

##### Ad Networks

By the 2000s, publishers were handling billions of impressions and thousands of advertisers. In this noisy space, a layer of service providers sprang up called ad networks. **Ad networks are companies which aggregate websites with comparable inventory into bundles, making it easier for advertisers to centralize their ad purchases.** This way advertisers could buy large numbers of ads to show to similar users visiting different websites, and more efficiently hit their impression targets (number of impressions they want their ads to make on viewers).

##### Ad Exchanges

All of this aggregation, and the mind-boggling number of impressions bundled, soon led to a confusing environment in which advertisers didn’t know where their ads were being placed or who was buying them.[18](https://www.cjr.org/tow_center_reports/the-guide-to-advertising-technology.php#citations) Soon enough, ad buyers sought more transparency around what they were getting for the money they were spending. This led to the creation of **ad “exchanges:” open platforms for comparing the price and quality of impressions and buying them.**



**The online advertising ecosystem**

![img](https://cdn.cjr.org/wp-content/uploads/2018/11/DisplayAdsGraphic-800x600.jpg)



## Other advertising formats 

In addition to the ad types noted above, several of the dominant sites (Google, Facebook, Instagram, Twitter, etc.) have their own formats. 

- For information on **Instagram ad formats**, see https://www.facebook.com/business/help/877053729032543?id=1997185213680277
- For information on **Twitter ad formats**, see https://marketing.twitter.com/na/en/solutions/ad-format-specs/promoted-tweet

- For information about **Google Mobile ad formats**, see https://support.google.com/google-ads/answer/2472719

## Displaying Google ads in mobile apps

Details about how to display google ads in a mobile app can be found here. https://support.google.com/google-ads/answer/1722057?hl=en

### Firebase as an advertising server

Firebase works with Google's AdMob to provide in app advertising. Ads can be sourced from Google directly, or from 40 ad networks through AdMob mediation. 

Ads can be displayed as banner ads, interstitial ads, video ads, or native ads — which are added to platform native UI components, and can be incorporated via Flutter widgets. 

**Note**: AdMob house ads can be used to cross-promote your apps to your user base, across your family of apps at no cost.

For information about using AdMob in Firebase, see: https://firebase.google.com/docs/admob