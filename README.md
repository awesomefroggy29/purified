<h5>purified is not affiliated with roblox.</h5>

<h2> this project isnt finished or released yet!!</h2>
<h4> if you would like to test this once it can be tested, please comment in https://github.com/awesomefroggy29/purified/issues/2 what computer you have, what cpu it has, and the page size of your os.</h4>
<h4> there is also a test website <a href="https://awesomefroggy29.github.io/purified">here</a> which i will probably update later once this project gets going.</h4>
<br>
<br>


# purified
<img width="128" height="128" alt="purified" src="https://github.com/user-attachments/assets/f5494e6a-41cb-4e83-9123-e1060f48704a" />

Roblox runtime for arm64 Linux which bridges the android version of roblox to native linux. This project is inspired by Sober.
Sober is working on an arm port, but it isnt their top priority. 


# Disclaimer
this project is being fully made with ai, or as people say, "vibe coded." this project is also currently in the works. it is not ready yet, but significant progress has shown. at first my goal was to launch the native roblox sign in screen, but i then realized that it would take longer than just using webview to launch roblox.com and simulate a web launch, which will skip the entire process of having to build the runtime for the sign in screen and main homepage. 

# Why am I making this?
roblox technically is possible to play on linux using something like waydroid, but there is many problems. ex: no proper mouse lock, laggier than native, and games think youre playing on mobile. this inspired me to have a go at this. however, i don't know how to code in c or c++. but you know who does? AI. so im making a runtime for roblox because people like running games on their pi.


# how does it work? 
__in simple terms:__
android is based on linux, which means that they share similarities in how the os works. this includes the types of executables they use, which are both ELF(executable and linkable format), and how they use them. this means you can create a runtime for a specific app to make it think its running in android.


# bro you suck why do you use ai
like i said, i dont know how to code in c++. and if you really dont like that i used ai, then its as simple as NOT USING THIS!!


# is there going to be a 32 bit arm version?
since roblox also makes apks for arm 32 bit, most likely, but maybe not. i dont know yet because i havent looked into it.


# is this ever going to be open source????? 
it is very unlikely, but there may be a possibility. The reason for this is because making this open source would likely lead to these problems:
<ul>
  <li>Roblox patching the workarounds to run roblox on linux</li>
  <li>abuse of the runtime to create bot farms</li>
  <li>spamming of issues in the code</li>
</ul>

<br>


# random questions you might have
"yo nice logo howd you make it?"
<br>
blender
<br>
<br>

# current progress:
refer to [project.md](https://github.com/awesomefroggy29/purified/blob/main/project.md) for a codex-generated project map and explanation of whats happening so far. 
<br>
# some images right now:
<img width="1920" height="1080" alt="Screenshot from 2026-05-24 07-30-27" src="https://github.com/user-attachments/assets/779f2a24-acca-4fdf-9a1d-27d6861e77b3" />
<img width="1920" height="1080" alt="Screenshot from 2026-05-24 07-32-47" src="https://github.com/user-attachments/assets/7a823e1f-d868-48d1-958e-bfb88e9444b5" />
<br>
the second screenshot is using webview to load the sign in screen. as explained above, it will be used for now as the homepage to launch games. 
