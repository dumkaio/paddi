### ❖ OVERVIEW
Paddi helps you to set paddings for a Group, a Frame, or a Component. When you specify the padding values in the component name you can change the elements inside the component and apply the paddings in one click. The component will automatically resize itself so that it surrounds all other elements within the component according to padding values.

Specify the padding values within the component group or frame name. E.g. button [12 24]. The format of the padding values is in the same order as CSS.

### ❖ FEATURES
✅ Paddi works with Groups, Frames, Components, Libraries.
✅ Paddi is simple! The only thing you need to do is specify the paddings in the component name
✅ Recognize components with paddings looking at their names. ⚡️ It works the same as in CSS.
✅ Paddi is flexible. No limitation there, set the same padding for all sides [12] or different for each one [12 24 14 32].
✅ Paddi uses a base element as a parent and calculates paddings from it.
✅ Speed up your workflow! You don’t need to open plugin settings all the time you need to update paddings. You only need to rename the component and run the Paddi.
✅ Natural master & instance behavior. If you change master component paddings, you don’t need to do anything else to update instances, Paddi will update all instances automatically.
✅ Paddi works with libraries. Create a master component in your library file and apply the padding for all its instances in any project file. ⚠️ If you change padding for the master component in the library you will have to update all instances in the other files manually.

### ❖ PADDINGS
Padding values sets by clockwise from top to left sides. It works the same as in CSS. Examples:
- [12] - padding for all sides - 12px
- [12 24] - top&bottom - 12px, right&left - 24 px
- [12 24 32] - top - 12px, right&left - 24px, bottom - 32px
- [12 24 32 16] - top - 12px, right - 24px, bottom - 32px, left - 16px

### ❖ FORMATS
We recommend to use space for separating padding values to keep it simple, however, you can use a comma as well. Examples:
- [12 24]
- [12, 24, 24, 12]

### ❖ SET PADDINGS FOR A GROUP
1. Create a rectangle. This element will be the base of the component
2. Put some text or another shape inside the rectangle
3. Group these elements
4. Select the Group and whether rename the Group by adding e.g. [16 32] at the end of the name or just run Paddi to apply the default values - [12 24]
5. Change text or resize elements inside the Group
6. Select the Group and run Paddi again to apply the paddings

### ❖ SET PADDINGS FOR A FRAME
1. Write some text or create a shape
2. Wrap it with a Frame
3. ⚠️ In case you have only one element in the Frame the paddings will calculate from the Frame to its element. ⚠️ In case you have more than 1 element inside the Frame and want to use this Frame as the base you need to wrap all its elements with a Group
4. Select the Frame and whether rename the Frame by adding e.g. [16 32] at the end of the name or just run Paddi to apply the default values - [12 24]
5. Change text or resize elements inside the Frame
6. Select the Frame and run Paddi again to apply the paddings

### ❖ SET PADDINGS FOR A COMPONENT
1. After you have a Group with some paddings create a master component from it
2. Set constraints for the master component to make sure its instances will responsive correctly. Set Scale for the base and make sure all other elements have Left and Top
3. Change elements and run Paddi. ⚠️ Because you can’t change elements position in an instance you will be able to change only the text elements and then apply the paddings

### ❖ IMPORTANT TO KNOW
⚠️ The lowest element in a group or frame is going to be the base of the component! So don't forget to add a base. 
⚠️ You can’t change paddings for instance because you can’t change its elements positioning. To handle it, go to the master component or detach the instance.
⚠️ If you want to set a Frame as a base and specify paddings for it, wrap all elements inside this frame in a group to have only one element in the frame and then apply Paddi.
⚠️ You can’t update paddings for several components at the same time, just yet. 

### ❖ WHERE TO USE
✅ Buttons
✅ Tab items
✅ Navigation items
✅ Dropdown menus
✅ Tags / Pils / Badges
✅ Tooltips / Popovers
✅ Icons
✅ UI Cards
✅ Modal dialogs
✅ Sections
✅ Etc.

### ❖ SHORTCUT FOR MAC OS
To speed up your workflow add a shortcut to Paddi. It takes a minute to set up but keeps a lot of time later on.
Open System Preferences -> Keyboard -> Shortcuts tab -> App Shortcuts -> Add new:
1. Application: Figma
2. Menu Title: Paddi
3. Keyboard shortcut: cmd+shift+P (You can use your own)

---

### 😎 MADE BY
Oleksandr Telnov & Mikhail Voloshin at Dumka.io