
<H1 align="center">Awesome Pods</H1>

# `iOS-awesome-pods`
## This project is aiming to list the most needed and awesome pods lib for iOS projects

# The Quickest Way to Show/Hide Hidden Files
Since the release of macOS Sierra, when in Finder, it is now possible to use the shortcut:
```ruby
 CMD + SHIFT + .
```
# Terminal
```ruby
  pwd to print the current path
```
# Modify text files in Terminal
```ruby
* Open File for edit
 $ vi filepath
 
* Input mode

 press i to enter the insert mode 
 press q coomand 
 
* Ex mode
To get into it, press Esc and then : (the colon).
 The cursor will go to the bottom of the screen at a colon prompt.
 Write your file by entering :w 
 and quit by entering :q
 You can combine these to save and exit by entering :wq
 However, if you're finished with your file, it's generally more convenient to type Shift-z-z from command mode

 write 
 :wq!   --> write and quite 
 :q!   quite without saving 
```

#### git
```ruby
using to generate .gitignore file 
https://www.gitignore.io/
```


```ruby
master git 

1- https://medium.freecodecamp.org/what-is-git-and-how-to-use-it-c341b049ae61

2- https://medium.freecodecamp.org/how-to-become-a-git-expert-e7c38bf54826

Create the branch on your local machine and switch in this branch :
$ git checkout -b [name_of_your_new_branch]

Change working branch :
$ git checkout [name_of_your_new_branch]


Push the branch on github :
$ git push origin [name_of_your_new_branch]


You can see all branches created by using :
$ git branch

Add a new remote for your branch :
The remote branch is automatically created when you push it to the remote server. So when you feel ready for it, you can just do:

git push <remote-name> <branch-name> 

Where <remote-name> is typically origin, the name which git gives to the remote you cloned from. Your colleagues would then just pull that branch, and it's automatically created locally.


After that, you can work locally in your branch, when you are ready to share the branch, push it. The next command push the branch to the remote repository origin and tracks it

git push -u origin your_branch
Teammates can reach your branch, by doing:

git fetch
git checkout origin/your_branch

You can continue working in the branch and pushing whenever you want without passing arguments to git push (argumentless git push will push the master to remote master, your_branch local to remote your_branch, etc...)

git push


Push changes from your commit into your branch :
$ git push [name_of_your_new_remote] [name_of_your_branch]

Update your branch when the original branch from official repository has been updated :
$ git fetch [name_of_your_remote]

Then you need to apply to merge changes, if your branch is derivated from develop you need to do :
$ git merge [name_of_your_remote]/develop

Delete a branch on your local filesystem :
$ git branch -d [name_of_your_new_branch]

To force the deletion of local branch on your filesystem :
$ git branch -D [name_of_your_new_branch]

Delete the branch on github :
$ git push origin :[name_of_your_new_branch]



More Ref
  https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches


Setting your branch to exactly match the remote branch can be done in two steps:

git fetch origin
git reset --hard origin/master


resets to the last committed state. In this case HEAD refers to the HEAD of your branch.
git reset --hard HEAD 



refresh new .git file for new user 

rm -rf .git

or 

git init for fresh one 

merg commit from terminal 
Simply doing the vim "save and quit" command :wq should do the trick.



Create a new repository
git clone https://Amr.Elghadban@git.itworx.com/mobility/PeopleSearch.git
cd PeopleSearch
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin https://Amr.Elghadban@git.itworx.com/mobility/PeopleSearch.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote add origin https://Amr.Elghadban@git.itworx.com/mobility/PeopleSearch.git
git push -u origin --all
git push -u origin --tags




#### ios-Open Project
https://github.com/dkhamsing/open-source-ios-apps


#### status bar
```ruby
   https://github.com/MaximKotliar/Bartinter
```

#### code Generator "R Swift"
```ruby
   https://github.com/mac-cain13/R.swift
```

#### gradient -> Slopy
```ruby
   https://github.com/mergesort/Slope?utm_campaign=AwesomeiOS%2BWeekly&utm_medium=email&utm_source=AwesomeiOS_Weekly_9
```

####  swizzling swift lumos
```ruby
   https://github.com/sushinoya/lumos
```

####  MVVM-C RxCoordinator Router 
```ruby
   https://github.com/quickbirdstudios/RxCoordinator
```
####  OpenSource Project fsnotes
```ruby
   https://github.com/glushchenko/fsnotes
```

#### Tag
```ruby
   https://github.com/kuler90/RKTagsView?fbclid=IwAR23-QfTBiPT0h-qagiM0GmCPiDejjgxrx-WvK3UfFo-N2k2qps9NWF0E3g
```

####  socket
```ruby
   https://github.com/daltoniam/Starscream?fbclid=IwAR2mv3v9uyulxKEDAJdqHLW9RCH0tbyPJUIxS_VlgbSGj7iQOB_krp-j2Gs
   https://github.com/adamhartford/SwiftR?fbclid=IwAR0b74Y3ZmYv43hMHmhm_CVXLdPGubByP52dfFcmfzDmnqVBQ0hBlApQCKM
   
```

#### SwifterSwift Extensions
```ruby
   pod 'SwifterSwift'            # All Extensions
   
   https://swifterswift.com/
```
#### Debuging
```ruby
  https://github.com/Flipboard/FLEX
```

### Loader skeleton indactor
```ruby
   https://github.com/Juanpe/SkeletonView
   
   https://github.com/Abedalkareem/AMShimmer
```

### OpenSource Projects 
# Quran القراءن
```ruby
https://github.com/quran/quran-ios?fbclid=IwAR3-ZLfGaN7VbvO2EML0y9iuUE7aSJfy0TFLfCKdG0177reGDcyJJ9mDsJE
```

#### XML HTML parsing
```ruby
https://github.com/scinfu/SwiftSoup?fbclid=IwAR3ji1p9L-vp2yg2jD_rzmNJw4lZMkjk4w_TFbtA7rgZ9v4xd-q57TvJdfo
```

#### ios-swift-libraries
```ruby
   https://infinum.co/the-capsized-eight/top-10-ios-swift-libraries-every-ios-developer-should-know-about
```

#### wrap encoding for struct
Wrap is an easy to use Swift JSON encoder. Don't spend hours writing JSON encoding code - just wrap it instead!

Using Wrap is as easy as calling wrap() on any instance of a class or struct that you wish to encode. It automatically encodes all of your type’s properties, including nested objects, collections, enums and more!
```ruby
   https://github.com/JohnSundell/Wrap
```

#### Unbox decoding for struct
```ruby
   https://github.com/JohnSundell/Unbox
```

#### Date tools
```ruby
   https://github.com/MatthewYork/DateTools
```

#### AttributedString  , NSAttributedString
```ruby
   https://github.com/malcommac/SwiftRichString
```

#### Working with Arrays and more
```ruby
   https://github.com/ankurp/Dollar
```
#### Working Linter swiftlint swiftformat
```ruby
  https://github.com/nicklockwood/SwiftFormat
```


#### Graphs / Charts
```ruby
   https://github.com/danielgindi/Charts/blob/master/README.md
```
#### SwiftMessages
```ruby
https://github.com/SwiftKickMobile/SwiftMessages
```

#### Error-Handling 
```ruby
https://github.com/Workable/swift-error-handler
```

#### keyboard handler
```ruby
pod 'IQKeyboardManagerSwift' #https://github.com/hackiftekhar/IQKeyboardManager
```
#### image compress size
```ruby
   https://github.com/hucool/WXImageCompress
```
####  ImagePicker  Gallery image
```ruby
   https://github.com/hyperoslo/Gallery
```

#### Network handler
```ruby
    pod 'Alamofire', '~> 4.4'     #https://www.raywenderlich.com/147086/alamofire-tutorial-getting-started-2    
    pod 'PromiseKit', '~> 4.4'
    pod 'kingfisher'   #for image downlaod  
    https://github.com/onevcat/Kingfisher/wiki/Cheat-Sheet#authentication-with-nsurlcredential
```
#### Localization
```ruby
    pod 'Localize-Swift', '~> 1.7'
```
#### Alerts
```ruby
    pod 'SCLAlertView'
```
#### Side Menu
```ruby
    pod 'SideMenu'
    
    https://github.com/jonkykong/SideMenu
```
#### Tab bar
```ruby
    https://github.com/itsKaynine/SwiftRaisedTab
```

#### Country Picker 
```ruby
    https://github.com/kizitonwose/CountryPickerView
```


#### collection 
```ruby
    https://github.com/ProudOfZiggy/SIFloatingCollection_Swift
```

#### UITextFiled
```ruby
    https://github.com/weilsonwonder/JVFloatLabeledTextField
```


#### Images
```ruby
    pod 'InitialsImageView'
```


#### Dashboard
```ruby
    https://www.cocoacontrols.com/controls/semi-circular-scale

 https://github.com/HamzaGhazouani/HGCircularSlider
```

#### UITextField
```ruby
    https://github.com/Skyscanner/SkyFloatingLabelTextField
```



#### animation   Ramotion
```ruby
    https://github.com/ameizi/awesome-ios-animation
    
    https://github.com/mmick66/kinieta

    https://github.com/Ramotion/swift-ui-animation-components-and-libraries
 
   https://github.com/onmyway133/fantastic-ios-animation
   
   https://github.com/HeroTransitions/Hero
   
```

#### Calendar
```ruby
    https://github.com/WenchaoD/FSCalendar
```

####  UI
```ruby
    https://github.com/Instagram/IGListKit
    https://github.com/texturegroup/texture
    https://github.com/springwong/SnapKitten 
```

#### How to use macOS Recovery
https://support.apple.com/en-eg/HT204904


Command (⌘)-R
Install the latest macOS that was installed on your Mac, without upgrading to a later version.*
Option-Command-R
Upgrade to the latest macOS that is compatible with your Mac.**
Shift-Option-Command-R
Requires macOS Sierra 10.12.4 or later	Install the macOS that came with your Mac, or the version closest to it that is still available. 





LICENSE
---
Distributed under the MIT License.

Contributions
---
Any contribution is more than welcome! You can contribute through pull requests and issues on GitHub.

Code of Conduct
---
I aim to share my knowledge and findings as i work daily to improve our apps, for our community, in a safe and open space. We work as we live, as kind and considerate human beings who learn and grow from giving and receiving positive, constructive feedback.

Author
---
If you wish to contact me, email @: amr.elghadban@gmail.com
