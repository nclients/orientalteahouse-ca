---
layout: "ssg-theme-astro/layouts/main.astro"  # This line of code should remain unchanged.
tag: "GTM-"
title: "Oriental Tea House 碧贵园功夫茶楼 - Best Food Today"
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
    - boldText: "1、招牌烤鸭特惠：$28.8。"
    - boldText: "2、午餐堂食特惠（周一至周五 11:00am~14:30pm）：$3.99"
    - text: " 黑豆酱排骨/迷你流心蛋挞/酱油米卷/猪肚粥/椰子冻。"
    - boldText: "3、晚餐堂食特惠（17:00pm~21:00pm）："
    - text: " 消费满 $98，即赠送小份 BBQ 猪肉或半只黄鸡
              消费满 $188，即赠送常规份 BBQ 猪肉或整只黄鸡"
    - smText: ""
  # add more text...
  textColor: "#ffffff"
  bgColor: "#E7383D"
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
    - { text: "首页", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "关于我们", link: "#about-us" }
    - { text: "联系我们", link: "#contact-us" }
    - { text: "English", link: "/" }
  # addOrderOnlineBtn: true
  # orderOnlineBtnInsteadText: "See MENU & Order"
  # addTableReservationBtn: false
  # tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "查看菜单并点餐"
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
      - "欢迎光临我们的餐厅！诚邀您品尝我们的美味佳肴！"
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

    btn1Text: "查看菜单并点餐"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=ec2722a9-334a-4304-bfb7-9a8d21433882" 
    btn2Text: "" 
    btn2Href: "" 

    bannerImg: ""
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    bottomInfo: "我们提供在线订餐服务"

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
      - "菜品展示"
    titleColor: "#000000"
    description: 
      - "Oriental Tea House 碧贵园功夫茶楼的所有菜品均采用精选优质食材新鲜制作，以最为优惠的价格为您提供高品质的美味。"
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
      - "关于我们"
    titleColor: "#000000"
    description: 
      - "欢迎光临Oriental Tea House 碧贵园功夫茶楼！这里是本地区最具代表性的中式和粤式美食餐厅之一。我们为您提供几乎所有想要的点心，确保每一道菜品都采用优质食材新鲜制作，价格合理。Oriental Tea House 碧贵园功夫茶楼还特别提供功夫茶——这一中国传统茶道的精髓，展现了中国人泡茶的独特风尚。制作功夫茶需要一套精美的茶具，包括茶壶、小茶杯等。我们诚邀您来体验这一经典的茶艺之旅。"
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
      - "欢迎光临"
      - "Oriental Tea House 碧貴園功夫茶樓 "
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
      - "新功能! 在线订餐"
    titleColor: "#ffffff"
    description: 
      - "现在支援线上订单自取。只要告诉我们您想要的菜肴，我们会​​尽快准备好。所有订单都由我们手动确认。您可以即时查看您的食物何时准备好。订单状态会即时更新，您可以在螢幕上查看您的食物何时可以取走。"
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
    telInsteadText: "电话：510-343-6588"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "导航"
 
 # The modal will only appear once within 30 minutes."
  - type: "modal" 
    bgColor: "#333"
    bgOpacity: "0.1" # 0~1
    title: 
      - "🎁 Special Offers"
    titleColor: "#FF2D2F"
    titleSize: 24
    description: 
      - "1、招牌烤鸭特惠：$28.8"
      - "2、午餐堂食特惠（周一至周五 11:00am~14:30pm）：$3.99
            黑豆酱排骨/迷你流心蛋挞/酱油米卷/猪肚粥/椰子冻"
      - "3、晚餐堂食特惠（17:00pm~21:00pm）：
            消费满 $98，即赠送小份 BBQ 猪肉或半只黄鸡
            消费满 $188，即赠送常规份 BBQ 猪肉或整只黄鸡"
    descriptionColor: ""
    descriptionSize: 16
    imgName: "碧貴園功夫茶樓 Oriental Tea House 24.webp"
    # imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
    # imgHref: ""
    # buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery/碧貴園功夫茶樓 Oriental Tea House 23.webp"
  bgColor: "#f3f4f6"
  bgOpacity: "0.8" # 0~1
  textColor: "#000" # default white

  openingHoursInsteadText: "营业时间"
  openingHours: 
    - "周一 ～ 周五:"
    - "11:30 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "周六 ～ 周日:"
    - "10:00 AM - 3:00 PM, 5:00 PM - 9:00 PM"
  
  isLogo: true
  logoSize: 90
 
  menu:
    - { text: "首页", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "关于我们", link: "#about-us" }
    - { text: "联系我们", link: "#contact-us" }
    - { text: "English", link: "/" }

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

  acceptedPaymentMethodsInsteadText: "支付方式"
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