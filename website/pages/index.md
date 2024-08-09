---
layout: "ssg-theme-astro/layouts/main.astro"  # This line of code should remain unchanged.
tag: "GTM-"
title: "Oriental Tea House 碧貴園功夫茶樓 - Best Food Today"
favicon: "favicon.ico"
logo: "logo.png"
primaryColor: "#6E2022" # logo color
secondaryColor: "#ffffff"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=ec2722a9-334a-4304-bfb7-9a8d21433882"
tableReservationLink: ""
tel: "510-562-2828"

banner:
  text: 
    # - boldText: "🥳 Special Offer"
    - boldText: "1.Roasted Duck special offer $28.8  "
    - boldText: "2.Lunch dine-in Specials Offer（Mon～Fri 11:00am~14:30pm): $3.99"
    - text: " ( Black Bean Sauce Spare rib, Mini Lava Custard Bun, Soy Rice Roll, Pork offal congee）Coconut Jelly"
    - boldText: "3.Dinner Dine-in special (17:00pm~21:00pm):"
    - text: " Get a free small dish of BBQ Pork or half yellow chicken when spending over $98.Get a free regular dish of BBQ Pork or one whole yellow chicken when spending over $188."
    - smText: ""
  # add more text...
  textColor: "#ffffff"
  bgColor: "#6E2022"
  bgOpacity: "1" # 0~1

# header
header:
  logoSize: 65
  textAfterLogo: 
    text: ""
    size: 16
    color: ""
  bgColor: "#ffffff"
  bgOpacity: "1" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  # addOrderOnlineBtn: true
  # orderOnlineBtnInsteadText: "See MENU & Order"
  # addTableReservationBtn: false
  # tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "See MENU & Order"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=ec2722a9-334a-4304-bfb7-9a8d21433882"
  otherBtn2InsteadText: ""
  otherBtn2Href: ""

sections:
# hero
  - type: "hero" 
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "video" # video | imgWithText | imgBg
    bgVideoType: "youtube" # youtube | vimeo | gjw
    bgVideoId: "9y93vPraw8I"
    bgImg: "gallery/碧貴園功夫茶樓 Oriental Tea House 23.webp"
    bgColor: "#000000"
    bgOpacity: "0.3" # 0~1
    title: 
      - "Oriental Tea House"
      - "碧貴園功夫茶樓"
    titleColor: "#ffffff"
    description: 
      - "Welcome to our restaurant! Come and try our dishes!"
    descriptionColor: "#ffffff"
    # title2: 
    #   - ""
    # title2Color: "#ffffff"
    # description2: 
    #   - ""
    # description2Color: "#ffffff"

    # addOrderOnlineBtn: false
    # orderOnlineBtnInsteadText: ""
    # addTableReservationBtn: false
    # tableReservationBtnInsteadText: ""

    btn1Text: "See MENU & Order"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=ec2722a9-334a-4304-bfb7-9a8d21433882" 
    btn2Text: "" 
    btn2Href: "" 

    bannerImg: ""
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    bottomInfo: "We offer Takeout"

# # Video
#   - type: "video"
#     id: ""
#     title: 
#       - "Lorem ipsum dolor sit amet"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et" 
#     videoType: "gjw" # vimeo | gjw | youtube
#     videoId: 
#       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
#       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
#     isOnlyDisplayOnMobile: false

# Gallery  
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Food at"
      - "Oriental Tea House 碧貴園功夫茶樓"
    titleColor: "#000000"
    description: 
      - "All dishes at Oriental Tea House are freshly prepared with premium ingredients at the lowest price."
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "sm" # sm | md | lg | xl | 2xl | 3xl | full


# textBlock - only title
  - type: "textBlock" 
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "About Us"
    titleColor: "#000000"
    description: 
      - "Welcome to Oriental Tea House! One of the best places for authentic Chinese/ Cantonese cuisine in this area. You can find almost all the dim sum you want here! All dishes at Oriental Tea House are freshly prepared with premium ingredients at the lowest price. We also serve Gong Fu tea. Gong Fu tea is the Chinese tea ceremony, the Chinese way of drinking tea. To make tea the Gong Fu way, we need a proper tea set. These are generally small tea utensils, like a teapot, small tea cups, and more.

"
    descriptionColor: ""

# Gallery  
  - type: "gallery"
    noMarginTop: false
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Welcome To"
      - "Oriental Tea House 碧貴園功夫茶樓"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery1"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "sm" # sm | md | lg | xl | 2xl | 3xl | full

# # feature - imgWithText
#   - type: "feature" 
#     noMarginTop: true
#     id: ""
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     title: 
#       - "Lorem ipsum dolor sit ame"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: ""
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""

#     btn1Text: "" 
#     btn1Href: "" 
#     btn2Text: "" 
#     btn2Href: "" 

#     bannerImg: "sample.webp"
#     imgPosition: "imgLeft" # imgLeft | imgRight
#     bannerMarginTopMobile: 20
#     imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# # feature - map
#   - type: "feature" 
#     id: ""
#     noMarginTop: false
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     title: 
#       - "Store 2 : Washington St"
#     titleColor: "#000000"
#     description: 
#       - "Opening Hours: "
#       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: true
#     orderOnlineBtnInsteadText: ""
#     addTableReservationBtn: true
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: true
#     btn1Text: "Order online from Washington St Store" 
#     btn1Href: "#" 
#     btn2Text: "" 
#     btn2Href: "" 

    # map: true
    # url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
    # iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
    # addTelBtn: true
    # tel: "12345678"
    # telInsteadText: "Call: (123) 456-7890"
    # tel2: "876543210" # if there are two phone numbers"
    # tel2InsteadText: "Call: (876) 543-2100"
    # getDirectionBtnInsteadText: ""
    # imgPosition: "" # imgLeft | imgRight




# # textBlock 
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "About Us"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

# textBlock - Information
  - type: "textBlock" 
    noMarginTop: false
    id: ""
    bgImg: "gallery/碧貴園功夫茶樓 Oriental Tea House 20.webp"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/LhisZy3Xt8QXEtvx5"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4295.262188366232!2d-122.14442501478744!3d37.73871099702607!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f8fa6f6e03753%3A0xb242047425731f65!2zT3JpZW50YWwgVGVhIEhvdXNlIOeip-i0teWbrS_noqfmoYLlm60!5e0!3m2!1szh-CN!2smy!4v1723042014875!5m2!1szh-CN!2smy"
    addTelBtn: true
    tel: "510-343-6588"
    telInsteadText: ""
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: ""
 
 # The modal will only appear once within 30 minutes."
  - type: "modal" 
    bgColor: "#333"
    bgOpacity: "0.1" # 0~1
    title: 
      - "🎁 Special Offers"
    titleColor: "#FF2D2F"
    titleSize: 24
    description: 
      - "1.Roasted Duck special offer $28.8.| "
      - "2.Lunch dine-in Specials Offer（Mon～Fri 11:00am~14:30pm): $3.99 ( Black Bean Sauce Spare rib, Mini Lava Custard Bun, Soy Rice Roll, Pork offal congee）Coconut Jelly.|"
      - "3.Dinner Dine-in special (17:00pm~21:00pm): Get a free small dish of BBQ Pork or half yellow chicken when spending over $98.Get a free regular dish of BBQ Pork or one whole yellow chicken when spending over $188."
    descriptionColor: ""
    descriptionSize: 16
    imgName: ""
    # imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
    # imgHref: ""
    # buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery/碧貴園功夫茶樓 Oriental Tea House 23.webp"
  bgColor: "#fff"
  bgOpacity: "0.8" # 0~1
  textColor: "#000" # default white

  openingHoursInsteadText: ""
  openingHours: 
    - "Monday - Friday:"
    - "11:30 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "Saturday - Sunday:"
    - "10:00 AM - 3:00 PM, 5:00 PM - 9:00 PM"
  
  isLogo: true
  logoSize: 90
 
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""

  acceptedPaymentMethodsInsteadText: ""
  paymentMethod: "cash,visa,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # at a minimum, please make sure to include the meta description.
  seo:
    metaDescription: "A Chinese restaurant located at 604 MacArthur Blvd San Leandro, CA, offers Cantonese and Dim Sum. We offer takeout." 
    keywords: ""
    img: ""
    thisPageUrl: ""
    locale: "en_US" # zh_TW | zh_CN
---
<!-- hello world -->