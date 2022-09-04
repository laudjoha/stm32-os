
# Dev Journal

I try to document in commits. Sometimes there is more context than a commit can adequately communicate, or I just want to talk about some microcontroller thing longer than my cat wants to listen to me. When that happens I write something here.

At the moment I am also using this to play around with Markdown because I need a reason to use it often enough that I can stop googling the same 5 things every time I need to do anything with it.

Not going to link everything here at the top, but like I said, this also exists for Markdown reference.

[Intro](#2022-09-03-23:46:57)

## 2022-09-03 23:46:57

My favorite thing about microcontrollers is that there are a lot of applications where a developer can conceivably know everything the computer does. The development speed and utility of libraries and frameworks enable some pretty impressive things. I have harnessed these things myself in computer vision applications. They are no match for the power and confidence that comes with knowing exactly how your custom computer works though.

I have worked on commercial projects that run proprietary real time OS's. I have kicked the tires on some FreeRTOS examples. I strongly prefer the design and organizational patterns you get with threads and schedulers vs superloops. I don't like the idea of paying for hobby time software, and I hate the idea of spending hobby time learning someone else's code (please don't respond "but what about resume building", I can't put my thoughts about spending personal hobby time on resume building in a public forum).

I do however, really enjoy "bottom up" learning. First principles baby! So I have [a book on operating systems that was published in 1974](https://www.sciencedirect.com/book/9780127017501/operating-systems), [Jonathan Valvano's website](http://users.ece.utexas.edu/~valvano/), and google. The goal here is not to make something as complete as FreeRTOS, or Zephyr, or any other common RTOS, it is to make something small and simple for my hobby applications. I want a pre-emptive scheduler. And maybe a low priority thread to queue and dump debug prints via uart... Or USB HID if we are feeling adventurous.

Thing I just did that I will probably forget by next time:

To insert date time in vs code
1. Install [Insert Date String Extension](https://marketplace.visualstudio.com/items?itemName=jsynowiec.vscode-insertdatestring)
2. Ctrl+Shift+p
3. Type 'Insert Date Time'

