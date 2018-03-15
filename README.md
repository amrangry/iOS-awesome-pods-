
<H1 align="center">Awesome Pods</H1>

# `iOS-awesome-pods`
## This project is aiming to list the most needed and awesome pods lib for iOS projects


#### git
```ruby

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

#### ios-Open Project
https://github.com/dkhamsing/open-source-ios-apps


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



#### keyboard handler
```ruby
pod 'IQKeyboardManagerSwift' #https://github.com/hackiftekhar/IQKeyboardManager
```

#### Network handler
```ruby
    pod 'Alamofire', '~> 4.4'     #https://www.raywenderlich.com/147086/alamofire-tutorial-getting-started-2    
    pod 'PromiseKit', '~> 4.4'
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
```


#### Tab bar
```ruby
    https://github.com/itsKaynine/SwiftRaisedTab
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



#### animation
```ruby
    https://github.com/ameizi/awesome-ios-animation
```

#### Calendar
```ruby
    https://github.com/WenchaoD/FSCalendar
```

#### .  UI
```ruby
    https://github.com/Instagram/IGListKit
    https://github.com/texturegroup/texture
    https://github.com/springwong/SnapKitten 
```


#### Animation 
```ruby
https://github.com/mmick66/kinieta
```





    





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
