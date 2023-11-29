# Tool Learning Log

Tool: **Unreal Engine**

Project: **First Person Shooter**

---

10/30/23:
* I went on the [xCode documentation website](https://developer.apple.com/documentation/xcode/) and I was trying to find what to start with. I found that xCode works in tandem with [SwiftUI](https://developer.apple.com/xcode/swiftui/).

* In addition to that, I followed up with watching [videos that Apple made](https://developer.apple.com/videos/developer-tools/) explaining more about xCode and there were some videos that may prove useful to me when I'm making my game like this [video](https://developer.apple.com/videos/play/wwdc2023/10279/) when they talk about how safari can be implemented in spatial computing or this [video](https://developer.apple.com/videos/play/wwdc2023/10125/) where it talks about how there is a [new optimized rendering engine](https://developer.apple.com/metal/) with spectacular performance.

* Some challenges that I faced were that xCode was quite demanding since it was owned by Apple. The coding language and [IDE](https://www.google.com/search?q=what+is+an+IDE&oq=what+is+an+IDE&gs_lcrp=EgZjaHJvbWUyCQgAEEUYORiABDIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDE2MjhqMGo5qAIAsAIA&sourceid=chrome&ie=UTF-8&safe=active&ssui=on) can only be accessed on Mac and not on any other [operating system](https://www.google.com/search?q=What+is+OS%3F&sca_esv=586169444&ei=bL5mZfmHDeDU5NoP5ZCBuAI&ved=0ahUKEwj57fr4r-iCAxVgKlkFHWVIACcQ4dUDCBA&uact=5&oq=What+is+OS%3F&gs_lp=Egxnd3Mtd2l6LXNlcnAiC1doYXQgaXMgT1M_MgsQABiABBiKBRiRAjILEAAYgAQYigUYkQIyCxAAGIAEGIoFGJECMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEjiF1AAWPMVcAV4AJABAJgBU6AB-weqAQIxNrgBA8gBAPgBAcICCxAAGIAEGLEDGIMBwgIREC4YgAQYsQMYgwEYxwEY0QPCAg4QLhiABBixAxjHARjRA8ICCBAAGIAEGLEDwgIREC4YgwEYkQIYsQMYgAQYigXCAgoQABiABBiKBRhDwgILEC4YgAQYxwEY0QPCAg4QABiABBiKBRixAxiDAcICIBAuGIMBGJECGLEDGIAEGIoFGJcFGNwEGN4EGOAE2AEBwgIHEAAYgAQYCsICDhAuGIAEGMcBGK8BGI4FwgINEAAYgAQYigUYsQMYQ8ICEBAAGIAEGIoFGLEDGIMBGEPCAggQABiABBjJA8ICCxAAGIAEGIoFGJIDwgIMEAAYgAQYigUYChhDwgIKEAAYgAQYsQMYCsICDRAAGIAEGLEDGMkDGArCAgsQABiABBiKBRixA-IDBBgAIEGIBgG6BgYIARABGBQ&sclient=gws-wiz-serp&safe=active&ssui=on) like [Windows](https://www.google.com/search?q=Windows+Operating+System&oq=Windows+Operating+System&gs_lcrp=EgZjaHJvbWUyCggAEAAYsQMYgAQyBggBEEUYOTIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDQxNzhqMGo5qAIAsAIA&sourceid=chrome&ie=UTF-8&safe=active&ssui=on).

* I found the solution to that problem quite easily by asking the school for a macbook and installed the [xCode IDE](https://developer.apple.com/xcode/features/) on it. The software was nice to work with and the simulator worked pretty well. It displayed an iPhone screen when simulated and it runs just like you would expect it to on phone. There was no need to have your own iPhone.

* While downloading xCode, I additionally found that there was an [app](https://developer.apple.com/swift-playgrounds/) that taught code and I opened it up. It was very intuitive and teaches the basics of code. It was a good first step in learning more about xCode and the structure of the coding language.

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


11/20/23:
* After researching on their documentation for a while, it is evident I need to include a SDK or something of the sort along with my project. It allows for more functions to be possible using the platform. Specifically for me, I may need the ARKit SDK because I need to make a game where it uses AR in order to pan the camera.

* I may need to learn more about Metal because it may be important to me since I am rendering things in Augmented Reality. Any three dimensional object may need to be passed through Metal in order for the game to work properly.


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
