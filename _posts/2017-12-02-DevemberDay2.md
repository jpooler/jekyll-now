---
published: true
---
## Ruby is fun

I found a couple of ruby repo's doing what I wanted, but the current state is mixed with the main one lacking updates for a few years. I cloned a fork and am getting familiar with the various libraries and plan to extend them/push changes up to github.

Currently the script is aware of other tasks running in the background/foreground, but allows for multiple copies to be run. I don't really see a need for this given it's purpose.

There's also a bunch of logic around progress mid-pomo, which I think defeats the purpose of this style of working and will be removed in subsequent updates. 

It's also designed to use a list of tasks, I want a more general purpose timer and will probably also remove this.

I'm hitting some "fun" rake issues because of the version of ruby used, which took a bit to figure out. Since I'm over the hour, I'll leave the list of things to do tomorrow here.

Todo:

1. Add default option to disable mid-pomo notifications
2. Add default timer with no task given
3. Add process detection logic to only allow one copy of pomo to be active.

-Jarrod
