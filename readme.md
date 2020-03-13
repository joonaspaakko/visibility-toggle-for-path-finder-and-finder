# Visibility toggle for Path Finder and Finder

![](visibility-toggle-path-finder.gif)

I used to use Total Finder before some performance issues in Mountain Lion (I think). It had this feature that I liked a lot called `Visor` and the way it worked was pretty simple: you could toggle Finder visibility with a shortcut and the Finder window would hide when another application was activated + you could also pin the window so that it wouldn't auto hide when another window gains focus. These scripts mimic this behavior in Path Finder and Finder.

The Alfred workflow (`Visibility toggle for Path Finder and Finder.alfredworkflow`) contains the two scripts for toggling the visibility of either Path Finder or Finder and this is all anyone should need. If you don't use alfred, see the bottom of the readme.

If you also want the application window to auto hide on deactivate, you can use the included Keyboard Maestro macros (`Auto hide + pin - Path Finder and Finder.kmmacros`).

> I use `Cmd + Shift + >` as my hide toggle shortcut (In my Finnish Swedish keyboard the `>` is the next button to the right from the left shift) and I use `Cmd + Shift + Ctrl + >` to disable auto hide.
>
> It's also possible to hide Path Finder and Finder icons from third party docks and application switchers. I use Witch from Many Tricks and Ubar.

____

I also included both visibility toggle scripts as plain AppleScript ( `Visibility toggle Path Finder.scpt` & `Visibility toggle Finder.scpt` ) in the repo for people who don't use Alfred. If you want the auto hide on deactivate behavior, it's either the Keyboard Maestro macros or you'll have to find other ways to do that.
