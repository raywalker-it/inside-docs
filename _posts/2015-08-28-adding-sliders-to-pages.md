---
layout: post
title: "Adding Sliders to Pages"
date: 2015-08-28 17:04:22
image: '/assets/img/'
description: Configuring Banner Sliders in Magento
tags:
categories: 
 - Banner Slider
twitter_text:
---

Now to place those [sliders]({% post_url 2015-08-28-adding-a-new-banner-slider %}) you've created in pages and categories and products. 

## Create the Shortcode Static Block 

- Navigate to _Banner Slider > Manage Banner Sliders_
- Click to select the **Shortcode for CMS** field for the slider you wish to use. The shortcode is the field which looks similar to: ![Shortcode for CMS](/assets/img/banner-slider/shortcode.png)
- While the shortcode is selected, press CTRL-C on the keyboard, or right click 'Copy to Clipboard'
- Navigate to _CMS > Static Blocks_ and click the **Add New Block** button
- Enter appropriate values in **Block Title** and **Identifier**
- Click the **Show / Hide Editor** button to hide all editor buttons
- Now paste the shortcode into the **Content** field by pressing CTRL-V, or right click 'Paste' ![Simple editor mode](/assets/img/banner-slider/editor.png)
- Click the **Save Block** button

## Add a Slider Block to a Category

- Select the category from _Manage Catalog > Manage Categories_
- Click the _Display Settings_ tab, and set **Display Mode** to either 'Static Block and Products' to display both the slider and products, or 'Static Block Only' to only display the slider without products.
- Select the slider from the **CMS Block** dropdown field
- Click the **Save Category** button
![Cateogory Slider](/assets/img/banner-slider/category.png)

