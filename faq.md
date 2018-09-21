---
title: FAQ
layout: blocks
date: 2017-11-22 23:00:00 +0000
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2018/09/03/logo1-1.png"
  navigation:
  - link: "/"
    link_text: Home
  - link: "#"
    link_text: Features
  - link: https://ctk2h-9a57rt2a.preview.forestry.io/pricing.html
    link_text: Pricing
  - link: https://ctk2h-9a57rt2a.preview.forestry.io/faq.html
    link_text: FAQ
  - link_text: Examples
  - link: https://ctk2h-9a57rt2a.preview.forestry.io/about.html
    link_text: About
  cta:
    url: www.platform.ai
    button_text: Join Beta
    undefined: "#9013FE"
  undefined: "#BD10E0"
- template: hero-banner-w-image
  block: hero-2
  headline: Platform.ai<strong><br>Deep Learning Anyone Can Use</strong>
  content: You got questions? We have answers!
  cta:
    enabled: true
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: Learn more
  image:
    image: "/uploads/2018/09/02/insurance.png"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: detail-content
  block: text-1
  headline: Is it really free for public projects?
  content: "<p>Yes, we want to do for deep learning, what Github did for open source
    software. If you share your data and models, you can use Platform for free.</p><p><br></p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: Once I train a model, what can I do with it?
  content: "<p>A trained model can be used to classify all of your images and produce
    a CSV file with the results. The model can also be used to classify new images
    from outside of the application using an API endpoint.</p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: Can I upload my own images?
  content: "<p>Yes, you can batch upload a collection of images from a local machine.
    Soon you will be able to upload your own images from these other sources: S3,
    GCS, Dropbox, etc.</p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: What if I have millions of images?
  content: "<p>No problem, Platform is designed to scale to very large collections
    of images.</p><p><br></p>"
- template: detail-content
  block: text-1
  headline: How are images billed?
  content: "<p>Images that are stored and used for (re)training are billed monthly.
    Images that are only used for prediction using the API end-point or CSV are billed
    only once.</p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: How fast are predictions?
  content: "<p>API end-point predictions are typically in the millisecond to a few
    seconds range.</p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: How many images do I need to hand label?
  content: "<p>With only a limited amount of hand-labeled images, you can build a
    classification model. However, the performance is dependent on the complexity
    of the use case. Some image sets require as little as 50 images per class for
    acceptable performance. As more images are labeled the accuracy of the model will
    improve. Platform displays the the current accuracy of the model so you can judge
    for yourself how many labels are needed.</p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: Can I deploy on-premise?
  content: <p>Yes, you can be deploy models trained on Platform in your own data center
    or private cloud. Get <a href="mailto:team@platform.ai">in touch</a> to request
    a model binary package.</p><p></p><p></p>
- template: detail-content
  block: text-1
  headline: Can I use platform to do something other than classification?
  content: "<p>Initially, Platform supports the training of models for image classification
    and similarity.</p><p>We are working to add other vision tasks with the intuitiveness
    of our classification user interface.</p><p></p><p></p>"
- template: detail-content
  block: text-1
  headline: Who owns the data and the models?
  content: "<p>If you have a paid account, you own the data and models. If you are
    using our free service, your images and models are available to Platform and other
    users.</p><p></p><p></p>"
- template: 3-column-text
  block: three-column-1
  col_1:
    headline: 1. Build
    content: Upload in your training data and Platform automatically builds you a
      custom deep learning model. Then refine your model by adjusting settings and
      connecting pre-trained building blocks.
  col_2:
    headline: 'Train '
    content: Monitor training progress in real-time with interactive charts and test
      results that update live as your model improves. Cloud training lets you get
      results quickly, without slowing down your computer.
  col_3:
    headline: Ship
    content: Export your trained model and do cool things with it
- template: signup-bar
  block: cta-bar
  background_color: "#380B5F"
  content: Sign up now and get running in minutes
- template: 4-column-footer
  block: footer-2
  col_2: "<strong>Platform</strong><br>Join Beta <br>Examples<br>About"
  col_3: "<strong>Legal</strong> <br>Privacy <br>Terms of Service "
  col_4: "<strong>Follow</strong><br>Twitter<br>Press kit<br>Facebook<br>Newsletter<br>Contact
    us "
  image: "/uploads/2018/09/03/logo1-1.png"

---
foo bar