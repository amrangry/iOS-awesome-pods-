

 <p align="center">
  <img src ="https://github.com/amrangry/iOS-awesome-pods-/blob/master/logo.jpeg?raw=true"/>
</p>
 
<H1 align="center">Awesome Pods</H1>

# `iOS-awesome-pods`
## This project is aiming to list the most needed and awesome pods lib for iOS projects

https://github.com/SwiftCairo/MeetupSessions/tree/master/13th%20meetup/Architecture%20Homicide
https://medium.com/swiftblade/using-swift-concurrency-with-coordinator-pattern-de290b95f09b
https://github.com/ProxymanApp/atlantis
https://ignatiojulian.medium.com/build-modularization-ios-application-dff1b69adf83
https://medium.com/@wil.barriost/ios-clean-architecture-my-way-on-a-very-simple-feature-mvvm-repository-urlsession-swift-678cfe4301f0

#### Markdown Cheatsheet : https://github.com/tchapi/markdown-cheatsheet
#### ios-swift-libraries : https://infinum.co/the-capsized-eight/top-10-ios-swift-libraries-every-ios-developer-should-know-about
#### Open Source iOS Project :
   * https://github.com/pointfreeco/isowords
   * https://github.com/dkhamsing/open-source-ios-apps
   * (fsnotes ) : https://github.com/glushchenko/fsnotes
   * ( Quran القراءن ) : https://github.com/quran/quran-ios

#### Swift Backend
   * https://github.com/FeatherCMS/feather
     <p align="center">
        <img src ="https://raw.githubusercontent.com/FeatherCMS/feather/main/Assets/GitHub-Lead.png?raw=true">
     </p>
   * https://github.com/BinaryBirds/swift-html
```
     import SwiftHtml 

     let doc = Document(.html) {
      Html {
        Head {
            Title("Hello Swift HTML DSL")
            
            Meta().charset("utf-8")
            Meta().name(.viewport).content("width=device-width, initial-scale=1")

            Link(rel: .stylesheet).href("./css/style.css")
        }
        Body {
            Main {
                Div {
                    Section {
                        Img(src: "./images/swift.png", alt: "Swift Logo")
                            .title("Picture of the Swift Logo")
                        H1("Lorem ipsum")
                            .class("red")
                        P("Lorem ipsum dolor sit amet, consectetur adipiscing elit.")
                            .class(["green", "blue"])
                            .spellcheck(false)
                    }

                    A("Download SwiftHtml now!")
                        .href("https://github.com/binarybirds/swift-html/")
                        .target(.blank)
                        .download()
                        
                    Abbr("WTFPL")
                        .title("Do What The Fuck You Want To Public License")
                }
            }
            .class("container")

            Script().src("./js/main.js").async()
        }
      }
     }
     let html = DocumentRenderer(minify: false, indent: 2).render(doc)
      print(html)
```

#### Design Pattern | Architecture
   * https://github.com/pointfreeco/swift-composable-architecture
   * https://github.com/ByteByteGoHq/system-design-101
     <p align="center">
        <img src ="https://github.com/ByteByteGoHq/system-design-101/blob/main/images/banner.jpg?raw=true">
     </p>
#### hide screen : https://github.com/marioIannotta/shyview
#### review app : https://github.com/ihamadfuad/AppStoreReviewsAPI
#### button : https://github.com/mrustaa/ButtonClickStyle
#### Tags tag
   * https://github.com/kuler90/RKTagsView
   * https://github.com/amrangry/TagsCollection
     <p align="center">
        <img src ="https://github.com/amrangry/TagsCollection/blob/main/logo.png?raw=true"/>
     </p>
  * https://github.com/dave-pang/TagStyledView  
   ![](Screenshot/demo.gif)
   * https://github.com/MakwanaRohit/ARSelectableView
   * https://www.cocoacontrols.com/controls/tagview-in-swift

#### SwiftUI
   * https://github.com/igbokwenu/ToonCards
![](https://user-images.githubusercontent.com/68666335/254692352-74966072-43c1-45c7-aae3-dd57283c600f.png)

#### bubble-pictures : https://www.cocoacontrols.com/controls/bubble-pictures-07d2c9b4-d768-485f-ac2e-b54dcb9c4189
#### lazy load : https://github.com/LeBzul/SimpleShimmer
#### capture uiview : https://github.com/startry/SwViewCapture
#### status bar : https://github.com/MaximKotliar/Bartinter
#### Chat : https://github.com/khuong291/Chatto
#### code Generator "R Swift" : https://github.com/mac-cain13/R.swift
#### gradient (Slopy) : https://github.com/mergesort/Slope?utm_campaign=AwesomeiOS%2BWeekly&utm_medium=email&utm_source=AwesomeiOS_Weekly_9
#### Swizzling swift lumos : https://github.com/sushinoya/lumos
#### VVM-C RxCoordinator Router : https://github.com/quickbirdstudios/RxCoordinator
#### UI Rate : https://github.com/ragaie/RateBar
#### animate : https://github.com/khuong291/MagicPresent
#### UI slider for collection :
   * https://github.com/shoheiyokoyama/Gemini
   * https://github.com/Yalantis/Koloda
   * https://github.com/amirdew/CollectionViewPagingLayout
#### SVG https://github.com/SVGKit/SVGKit
#### XML HTML parsing : https://github.com/scinfu/SwiftSoup
#### AttributedString , NSAttributedString :  https://github.com/malcommac/SwiftRichString
#### Working with Arrays and more : https://github.com/ankurp/Dollar
#### Working Linter swiftlint swiftformat : https://github.com/nicklockwood/SwiftFormat
#### QRCodeReader : https://github.com/yannickl/QRCodeReader.swift
#### Graphs / Charts : https://github.com/danielgindi/Charts/blob/master/README.md
#### SwiftMessages : https://github.com/SwiftKickMobile/SwiftMessages
#### Error-Handling : https://github.com/Workable/swift-error-handler
#### keyboard handler IQKeyboardManagerSwift : #https://github.com/hackiftekhar/IQKeyboardManager
#### BlurView : https://github.com/KyoheiG3/DynamicBlurView
#### image compress size : https://github.com/hucool/WXImageCompress
#### Side Menu SideMenu https://github.com/jonkykong/SideMenu
#### Panel : https://github.com/SCENEE/FloatingPanel
#### Country Picker : https://github.com/kizitonwose/CountryPickerView
#### collection : https://github.com/ProudOfZiggy/SIFloatingCollection_Swift
#### Images : 'InitialsImageView'
#### Badge :  https://github.com/MatrixSenpai/BadgeHub
#### Calendar : https://github.com/WenchaoD/FSCalendar
#### Localization : pod 'Localize-Swift', '~> 1.7'
#### Screenshot || ScreenshotPreventing || preventing
* [ScreenshotPreventing](https://github.com/yoxisem544/ScreenshotPreventing-iOS)
  
<img src="https://github.com/yoxisem544/ScreenshotPreventing-iOS/blob/main/Assets/demo.gif" width="470" />

#### Alerts || Screen || Popup || Messages
 * [SCLAlertView](https://github.com/pmusolino/PMAlertController)
 * [popup View](https://github.com/exyte/PopupView)

   <table>
    <thead>
        <tr>
            <th>Floaters</th>
            <th>Toasts</th>
            <th>Popups</th>
            <th>Sheets</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <img src="https://raw.githubusercontent.com/exyte/media/master/PopupView/1.gif" />
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/exyte/media/master/PopupView/2.gif" />
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/exyte/media/master/PopupView/3.gif" />
            </td>
            <td>
                <img src="https://raw.githubusercontent.com/exyte/media/master/PopupView/4.gif" />
            </td>
        </tr>
    </tbody>
</table>
   

#### SwifterSwift Extensions POD : https://swifterswift.com/
#### Debuging  https://github.com/Flipboard/FLEX
#### Date : 
 * https://github.com/malcommac/SwiftDate
 * https://github.com/MatthewYork/DateTools
 * https://github.com/toure20/RealTimePicker
#### SwipeCellKit for UITableView + UIcollectionView
 * https://github.com/SwipeCellKit/SwipeCellKit
 * https://www.cocoacontrols.com/controls/upcarouselflowlayout
 * https://github.com/ink-spot/UPCarouselFlowLayout
#### socket
 * https://github.com/daltoniam/Starscream
 * https://github.com/adamhartford/SwiftR
#### Loader skeleton indactor
 * https://github.com/Juanpe/SkeletonView
 * https://github.com/Abedalkareem/AMShimmer
####  ImagePicker  Gallery image
 * https://github.com/hyperoslo/Gallery
 * https://github.com/hyperoslo/ImagePicker
 * https://github.com/mikaoj/BSImagePicker
#### Network handler
 * Alamofire' #https://www.raywenderlich.com/147086/alamofire-tutorial-getting-started-2    
 * 'PromiseKit'
 * 'kingfisher' #for image downlaod  https://github.com/onevcat/Kingfisher/wiki/Cheat-Sheet#authentication-with-nsurlcredential
#### Dashboard 
 * https://www.cocoacontrols.com/controls/semi-circular-scale
 * https://github.com/HamzaGhazouani/HGCircularSlider
#### UITextField
 * https://github.com/Skyscanner/SkyFloatingLabelTextField
 * https://github.com/weilsonwonder/JVFloatLabeledTextField
 * https://github.com/ilyapuchka/ReadMoreTextView
#### animation   Ramotion
 * https://github.com/ameizi/awesome-ios-animation
 * https://github.com/mmick66/kinieta
 * https://github.com/Ramotion/swift-ui-animation-components-and-libraries
 * https://github.com/onmyway133/fantastic-ios-animation
#### UI
 * https://github.com/Instagram/IGListKit
 * https://github.com/texturegroup/texture
 * https://github.com/springwong/SnapKitten 
#### Tab bar : https://github.com/itsKaynine/SwiftRaisedTab
#### Tab (Parchment) : 
 * https://github.com/rechsteiner/Parchment
<p align="center">
  <img src="https://raw.githubusercontent.com/rechsteiner/Parchment/main/.images/example-cities.gif" alt="Cities Example" />
  <img src="https://raw.githubusercontent.com/rechsteiner/Parchment/main/.images/example-unsplash.gif" alt="Unsplash Example" />
  <img src="https://raw.githubusercontent.com/rechsteiner/Parchment/main/.images/example-calendar.gif" alt="Calendar Example" />
</p>

 * https://www.cocoacontrols.com/controls/oneway
 * https://github.com/git-chglog/git-chglog
 * https://github.com/amrangry/iOS_build_Issues

 * https://github.com/popei69/TemplateProject
 * https://github.com/github/gitignore
 * https://github.com/amrangry/canvas_demo
 * https://github.com/amrangry/dev_macOS_environment_setup
 * https://github.com/amrangry/ClockWise
 * https://github.com/amrangry/amrangry.github.io
 * https://github.com/amrangry/SVProgressHUD
 * https://github.com/amrangry/CWRateKit
 * https://github.com/amrangry/MGStarRatingView
 * https://github.com/amrangry/AASignatureView
 * https://github.com/amrangry/FloatRatingView

 * https://github.com/varun-naharia/VNImageScanner
 * https://github.com/amrangry/HTML_Redirect_Screen
 * https://github.com/rsrbk/GoSwifty
 * https://github.com/amrangry/DesignSystem
 * https://github.com/amrangry/SwiftConnect

 * https://github.com/appcoda/NSOperation-Demo
 * https://github.com/opentrace-community/opentrace-ios
 * https://github.com/yonaskolb/Mint
 * https://github.com/SnapKit/SnapKit
 * https://github.com/amrangry/DynamicLink
 * https://github.com/schmidyy/Loaf
 * https://github.com/optonaut/ActiveLabel.swift
 * https://github.com/Ramotion/animated-tab-bar
 * https://github.com/Yalantis/Koloda
 * https://github.com/kerollesroshdi/KRTabBar
 * https://github.com/evgenyneu/keychain-swift
 * https://github.com/ActionKit/ActionKit
 * https://github.com/antonyraphel/ARCarMovement
 * https://github.com/nicklockwood/iCarousel
 * https://github.com/amrangry/SideMenu
 * https://github.com/yassram/YRPayment

 * https://github.com/amrangry/DynamicHeightCollectionView
 * https://github.com/amrangry/GPVideoPlayer
 * https://github.com/amrangry/ScreenCaptureDetector
 * https://github.com/amrangry/momento
 * https://github.com/MohamedHusseinIOS/tahrirLounge

 * https://github.com/amrangry/MotoShop
 * https://github.com/amrangry/CI_CD_Tutorial
 * https://github.com/amrangry/tranxit_user
 * https://github.com/amrangry/Tranxit_Driver
 * https://github.com/amrangry/Awoon_iOS

 * https://github.com/amrangry/POSRetail_iOS
 * https://github.com/amrangry/POSRetail_Php
 * https://github.com/amrangry/DubaiWatchWeek_QRCode
 * https://github.com/amrangry/StockApp
 * https://github.com/amrangry/Financial-Dashboard_iOS
 * https://github.com/amrangry/Financial-Dashboard_Php
 * https://github.com/amrangry/WebBrowserApp
 * https://github.com/amrangry/Seddiqi_logistics_php
 * https://github.com/amrangry/Seddiqi_Logistics

 * https://github.com/amrangry/QKMRZScanner

 * https://github.com/amrangry/QuickDialog
 * https://github.com/amrangry/FolioReaderKit

 * https://github.com/amrangry/ePubReader
 * https://github.com/amrangry/ePub_Reader_POC
 * https://github.com/amrangry/ePub_Redaer_POC_2

Open Source contribution
---
 * https://github.com/amrangry/SwiftyMenu : https://github.com/KarimEbrahemAbdelaziz/SwiftyMenu/graphs/contributors
 * https://github.com/amrangry/BadgeHub : https://github.com/jogendra/BadgeHub/graphs/contributors


My Open Projects
---
 * https://github.com/amrangry/ios-task
 * https://github.com/omerio/android-interview-questions
 * https://github.com/omerio/iOS-Interview-Questions
 * https://github.com/mister0/How-to-prepare-for-google-interview-SWE-SRE
 * 
 * https://github.com/duraki/SketchCrapp
 * https://github.com/maciekish/iReSign
 * https://github.com/noodlewerk/NWPusher
 * 
 * https://github.com/amrangry/FileCaching
 * https://github.com/amrangry/ImagePickerHandler
 * 
 * https://github.com/amrangry/Marvel_iOSApp
 * https://github.com/amrangry/GoEuroDemo
 * https://github.com/amrangry/CustomerSearchBar
 * https://github.com/amrangry/JailBrokenCheckerUtility
 * https://github.com/amrangry/GoogleMaps_ios_UberLike
 * https://github.com/amrangry/backbase
 * https://github.com/amrangry/RealEstates_demo
 * https://github.com/amrangry/NYTimes
 * https://github.com/amrangry/iCar
 * https://github.com/amrangry/zadcall_voximplant_ios_demo
 * https://github.com/amrangry/iOS_Firebase_PushNotification_Sample
 * https://github.com/amrangry/TagsCollection

 
 
 
## **Author**

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/2900952?s=400&u=41c504ca200e2f92638fc630e8361da78296b35c&v=4" width="180" alt="Amr Ahmed Elghadban"/>

  **Amr Ahmed Elghadban (AmrAngry)**

[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?logo=gmail)](mailto:amr.elghadban@gmail.com) [![WhatsApp](https://img.shields.io/badge/GitHub-Profile-blue?logo=whatsapp)](https://api.whatsapp.com/send/?phone=00971543233227&text=Hi%20&app_absent=0) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/amrelghadban/)

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/amrangry) [![StackOverflow](https://img.shields.io/badge/StackOverflow-Profile-orange?logo=stackoverflow)](https://stackoverflow.com/users/1316779/amrangry)

[![Twitter (formerly Twitter)](https://img.shields.io/badge/Twitter-Profile-blue?logo=twitter)](https://x.com/intent/follow?screen_name=amr_elghadban) [![Facebook](https://img.shields.io/badge/Facebook-Profile-blue?logo=facebook)](https://facebook.com/amr.elghadban) [![Website](https://img.shields.io/badge/Website-Visit%20Me-blue?logo=globe)](https://amrangry.github.io/)
       <div align="center" >
	       <a href = "https://www.buymeacoffee.com/amrangry">
		    <img src = "https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=your-username&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"/>
                </a>
       </div>
  <!--  [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20Me-yellow?logo=buymeacoffee)](https://www.buymeacoffee.com/amrangry) -->
  <!--  [Email](mailto:amr.elghadban@gmail.com?subject=I%20checked%20your%20GitHub%20repo!): [amr.elghadban@gmail.com](mailto:amr.elghadban@gmail.com) -->
  <!-- [![Linkedin](https://img.shields.io/badge/Lets%20Connect%20via-LinkedIn-blue)](https://www.linkedin.com/in/amrelghadban/) -->
  <!-- [![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/amr_elghadban)](https://x.com/intent/follow?screen_name=amr_elghadban) -->
  
</div>

## **Contributing 🤘**

All your feedback and help to improve this project is very welcome. Please create issues for your bugs, ideas and enhancement requests, or better yet, contribute directly by creating a PR. 😎

When reporting an issue, please add a detailed instruction, and if possible a code snippet or test that can be used as a reproducer of your problem. 💥

When creating a pull request, please adhere to the current coding style where possible, and create tests with your code so it keeps providing an awesome test coverage level 💪

## **Code of Conduct**

I’m here to share my knowledge and findings as I work every day to improve our apps/demos for the community.
This is a space where we work together, openly and safely, as kind and considerate human beings.
We grow by giving and receiving positive, constructive feedback. 
Let’s keep learning and building, one step at a time.

## **License**

<details>
<summary>MIT License.</summary>
Distributed under MIT License.
Copyright 2025 © Amr Elghadban
</details>




