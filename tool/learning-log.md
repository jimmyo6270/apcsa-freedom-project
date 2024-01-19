# Tool Learning Log

Tool: **Unreal Engine**

Project: **First Person Shooter**

---

### 10/30/23:

* I went on the [xCode documentation website](https://developer.apple.com/documentation/xcode/) and I was trying to find what to start with. I found that xCode works in tandem with [SwiftUI](https://developer.apple.com/xcode/swiftui/).

* Some challenges that I faced were that xCode was quite demanding since it was owned by Apple. The coding language and [IDE](https://www.google.com/search?q=what+is+an+IDE&oq=what+is+an+IDE&gs_lcrp=EgZjaHJvbWUyCQgAEEUYORiABDIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDE2MjhqMGo5qAIAsAIA&sourceid=chrome&ie=UTF-8&safe=active&ssui=on) can only be accessed on Mac and not on any other [operating system](https://www.google.com/search?q=What+is+OS%3F&sca_esv=586169444&ei=bL5mZfmHDeDU5NoP5ZCBuAI&ved=0ahUKEwj57fr4r-iCAxVgKlkFHWVIACcQ4dUDCBA&uact=5&oq=What+is+OS%3F&gs_lp=Egxnd3Mtd2l6LXNlcnAiC1doYXQgaXMgT1M_MgsQABiABBiKBRiRAjILEAAYgAQYigUYkQIyCxAAGIAEGIoFGJECMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEjiF1AAWPMVcAV4AJABAJgBU6AB-weqAQIxNrgBA8gBAPgBAcICCxAAGIAEGLEDGIMBwgIREC4YgAQYsQMYgwEYxwEY0QPCAg4QLhiABBixAxjHARjRA8ICCBAAGIAEGLEDwgIREC4YgwEYkQIYsQMYgAQYigXCAgoQABiABBiKBRhDwgILEC4YgAQYxwEY0QPCAg4QABiABBiKBRixAxiDAcICIBAuGIMBGJECGLEDGIAEGIoFGJcFGNwEGN4EGOAE2AEBwgIHEAAYgAQYCsICDhAuGIAEGMcBGK8BGI4FwgINEAAYgAQYigUYsQMYQ8ICEBAAGIAEGIoFGLEDGIMBGEPCAggQABiABBjJA8ICCxAAGIAEGIoFGJIDwgIMEAAYgAQYigUYChhDwgIKEAAYgAQYsQMYCsICDRAAGIAEGLEDGMkDGArCAgsQABiABBiKBRixA-IDBBgAIEGIBgG6BgYIARABGBQ&sclient=gws-wiz-serp&safe=active&ssui=on) like [Windows](https://www.google.com/search?q=Windows+Operating+System&oq=Windows+Operating+System&gs_lcrp=EgZjaHJvbWUyCggAEAAYsQMYgAQyBggBEEUYOTIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDQxNzhqMGo5qAIAsAIA&sourceid=chrome&ie=UTF-8&safe=active&ssui=on).

* I found the solution to that problem quite easily by asking the school for a macbook and installed the [xCode IDE](https://developer.apple.com/xcode/features/) on it. The software was nice to work with and the simulator worked pretty well. It displayed an iPhone screen when simulated and it runs just like you would expect it to on phone. There was no need to have your own iPhone.

* When I booted up xCode, I made a project and it booted me into the workspace. I played around with it trying new code that I found from the documents like adding a circle into the preview:

```
import SwiftUI


struct MeetingTimerView: View {
    var body: some View {
        Circle()
            .strokeBorder(lineWidth: 24)
            .overlay {
                Text("Placeholder")
            }
    }
}
```
* It says that xCode supports C, C++, Objective-C, Objective-C++, Java, AppleScript, Python, Ruby, ResEdit (Rez), and Swift. For me, it means I have lots of options when it comes to what to make and how I want to make it.

* I'm going to dig deeper into the Apple xCode documentation and find more things that I need in order to make this shooter game come to life.


### 11/20/23:

* After researching on their documentation for a while, it is evident I need to include a SDK or something of the sort along with my project. It allows for more functions to be possible using the platform. Specifically for me, I may need the ARKit SDK because I need to make a game where it uses AR in order to pan the camera.

* I may need to learn more about Metal because it may be important to me since I am rendering things in Augmented Reality. Any three dimensional object may need to be passed through Metal in order for the game to work properly.

* In addition to that, I followed up with watching [videos that Apple made](https://developer.apple.com/videos/developer-tools/) explaining more about xCode and there were some videos that may prove useful to me when I'm making my game like this [video](https://developer.apple.com/videos/play/wwdc2023/10279/) when they talk about how safari can be implemented in spatial computing or this [video](https://developer.apple.com/videos/play/wwdc2023/10125/) where it talks about how there is a [new optimized rendering engine](https://developer.apple.com/metal/) with spectacular performance.

* While downloading xCode, I additionally found that there was an [app](https://developer.apple.com/swift-playgrounds/) that taught code and I opened it up. It was very intuitive and teaches the basics of code. It was a good first step in learning more about xCode and the structure of the coding language.

* After playing around with the simple Swift Playgrounds scenarios, I started to dive deeper into the more complciated scenarios like the ones called "Animating Shapes". It teaches me how to make code to create geometrical shapes like circles and dots or animating something to enable drag and drop.

* I learned that the structure of the code and the methods are all pretty much the same as Java and Javascript. It has things like:

```
funct resetValues() {
    scaleFactor = 1
    offset = .zero
}
```
* Though, there are some subtle differences like every line of code does not need to be ending with a semicolon.

* Swift has syntax that is easy to understand and I believe it's easier to understand. There are some snippets where it is pretty self explanitory with the words that they use.

### 12/4/23:

* I found the documentation for Apple's augmented reality SDK named RealityKit [here](https://developer.apple.com/documentation/realitykit/)

* I also needed understanding of the ARKit in order to make RealityKit work.

* There are a wide range of things like games, simulation, video playback, etc on the RealityKit documentation.

* I watched apple's realitykit introduction [here](https://developer.apple.com/videos/play/wwdc2023/10080/).

* I also watched a youtube video on how to start off with using RealityKit to create my game [here](https://www.youtube.com/watch?v=Fd_0gtV8RiY). this introduced to me things like how xcode has a built in starter kit for RealityKit, already providing some code as a brief example on how to use RealityKit and make something display.

*  I tried it myself and I used my own phone as a camera for the RealityKit to work. It ended up working perfectly fine and it displayed an actual block.

### 12/11/23

* Researching more about my tool, I noticed that I should implement swiftui and realitykit in the same app at the same time. I watched this [video](https://youtu.be/cT8y7fNEMuw?si=2zNw73hB7lqkX7fU) to help me understand more about how I can create visual ui on top of the camera so I can display buttons and stuff like that while the augmented reality is still working on the bottom.

* I read more on the [swiftui documentation](https://developer.apple.com/documentation/swiftui/) and I found some things like an introduction to visionOS [here](https://developer.apple.com/documentation/visionOS/World). I might find it important later on as I want something like a movable ui within the augmented reality.

* I read more about [windows](https://developer.apple.com/documentation/swiftui/windows), [toolbars](https://developer.apple.com/documentation/swiftui/toolbars), and [search function](https://developer.apple.com/documentation/swiftui/search) for the app that I will make. Windows can help me make different tabs of text that people can multitask and be able to read multiple things all at once. Toolbars can help me with giving the user more options for menus and interactive buttons on screen. Search function can be an addition to everything else so it can give the user ease or maybe if I made my game multiplayer, I can make a search function for something like a player finder.

* SwiftUI has something like a [hierarchy](https://developer.apple.com/documentation/swiftui/view-fundamentals) for when UI is displayed. This is probably like the Z coordinate value on HTML and CSS. It probably prioritizes what comes first and what comes after. This might be helpful since I can prioritize what the user needs to know on top instead of everything being messy.

* [Images](https://developer.apple.com/documentation/swiftui/images) and [Text input output](https://developer.apple.com/documentation/swiftui/text-input-and-output) is definetly needed whenever I need to make something interactive on my app.

### 1/2/24

* I used [SwiftStrike](https://developer.apple.com/documentation/realitykit/swiftstrike_creating_a_game_with_realitykit) to teach me how to make a game using realitykit. I installed it and tried using it.

* I believed that SwiftUI documentation was too confusing and the [app](https://developer.apple.com/swift-playgrounds/) that I used to learn SwiftUI took too long. I decided to watch more youtube tutorials and use this website named ["Hacking with Swift"](https://developer.apple.com/swift-playgrounds/). It helped me with many things like explaining what SwiftUI did and more in depth explainations that were also simple enough for me to understand.

Some videos I watched were:

* [2021 SwiftUI Tutorial for Beginners](https://www.youtube.com/watch?v=F2ojC6TNwws)
* [ SwifftUI Findamentals | FULL COURSE | Beginner Friendly](https://www.youtube.com/watch?v=b1oC7sLIgpI)
* (Playlist) [SwiftUI Tutorials for Beginners](https://www.youtube.com/playlist?list=PLMRqhzcHGw1Z-lZaaun3A3mV9PbEfHANI)
* (Playlist) [SwiftUI Tutorials](https://www.youtube.com/playlist?list=PLMRqhzcHGw1Z-lZaaun3A3mV9PbEfHANI)

### 1/16/24

* Once I familiarized myself with SwiftUI, I decided to watch more youtube videos on RealityKit.

Some videos I watched:

* [This video taught me how to create a simple app](https://www.youtube.com/watch?v=jjCsI56XavI)
* (Playlist) [Mobile Apple AR Tutorials (RealityKit/ArKit/SwiftUI)](https://www.youtube.com/playlist?list=PLb0SG4T4tfPyQF-hMntGxaKqUJOKZQ2QX)
* [giving me insight on how I can apply realitykit to my app](https://developer.apple.com/videos/play/wwdc2023/10080/)


