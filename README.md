
## ![](https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-studio-common/plateau-studio/party-horn.svg) **New Features**

### Features on Plateau Studio


- To **Start Learning** app development on Plateau Studio, follow steps in our new **App Development Starter Guide & MiniApp Development Starter Guide** documentation which you can access via the Landing page and Plateau Studio Docs.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/AppDevStarterGuide1.jpg" width="640" />


- **Quick Start to Development Video Set** is on live. You can start learn to develop your own application with our new video set on Youtube.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/YoutubeVideo.jpg" width="640" />


- You can now enjoy Plateau Studio's new **Landing Page** where yo can easily access to our Features, Login Page, Start Learning, Watch Series and Documentation. 
 <img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/welcomePage.png" width="640" />


- **Plateau Studio's Login Page** now has a new responsive design!

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/LoginPage.jpg" width="640" />
 
- Versioning is now offered as a separate feature under the **Save and Version** option, **independent of the Stop Working**. This allows you to speed up your Stop Working tasks by performing versioning only when necessary.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/save-and-version.png" width="640" />

- Packaging configuration have been updated to use the production mode. As a result, Plateau Studio is now minified and optimized for better performance. The startup times of small and medium-sized applications have been accelerated by 50% and large applications by 30%.

- **Electric Vehicle Charge Application Template** added for faster **MiniApp Development**.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/miniapptemp.jpg" width="640" />

- **Dataroid Integration** is now available for application working with Plateau Studio SDK and **MiniApps**. Integrate Dataroid in your shell/main application working with Plateau Studio SDK and manage development on Plateau Studio. For more information on Dataroid Integration, click <a class="doc-link" href="https://docs.onplateau.com/UI-Screens/UI-Settings/Integrations/dataroid-integration" target="_blank"> See More </a>.

```ts
quick.integrations.Dataroid.track("customEvent", {param1: "", param2: undefined })
```
<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/dataroidCard.jpg" width="640"  />

- **Unassign** feature added. Organization and organization group owners are now allowed to **unassign pages** from users that currently working on the page. 

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/unassign.png" width="640" />
  
- The **warning text** users interface changed for better user experience on the **Export and Publish** screens

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/warningExport.png" width="640" />



- Some improvements made in Plateau Studio **Documentation**
    - Info cards for Rest Service Calling, Format & Masking and various improvements made.
    - Use cases and info cards added to highlight the important component behaviors specific to **mobile development** for VRadio, VSelect, DocumentViewer components.

**For Warnings cards:** 

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/CompWarning.png" width="640" />

**For Mobile Usage cards:**

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/CompMobileUse.png" width="640" />



- The **Mobile App Preview QRCode** size expanded for ease of use. 

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/QRcode.jpg" width="640" />

- Rendering Component UI/UX enhancements completed by adding an icon and message indicating that the page is empty.


- You can now **resize the application explorer tree**.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/resize.gif" width="640" />



### Features on UI Editor

- **Encryption features; hash(), encrypt(), decrypt()** introduced to securely manage data sent to the backend from the UI. For more details on each methods, click See More. (LINK)

- **VCol component** can now only have **VRow as a parent component**.
<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/VCol.gif" width="640" />

- The **Help and Settings buttons** removed from the UI editor. You can use Plateau Studio Documentation, ChatBot and application UI Settings instead.

- The **VFooter** component now appears as a template for both **mobile and web** when added to the page.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/VFooterTemplate.gif" width="640" />

- The **VCard, VSheet and VImg components** now have **Style z-index** and **position properties**.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/positionComp.gif" width="640" />

- In the style component's input areas, when no default value was set, the input boxes defaulted to 0. If the entered value was deleted, it resets to 0. Now, **if there's no default value, the fields are left empty**. When the entered value is deleted, the content becomes empty as well.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/inputFields.gif" width="640" />

- Props below removed/moved from **VRadio components**: 
  - **Font props (FontFamily- FontSize-FontColor-FontStyle)** in the VRadio component,
  - **Border prop (Default, Selected)** removed in VRadio component,
  - **Box size prop** in the VRadio component moved to the VRadioGroup component.
    
- You can now block the requests to Google Fonts by adding the **blockFontRequest** parameter in the **settings.yaml file.**


```ts
    blockFontRequest: true
```


- **Footer component** now can only accept **Carousel** as it's child component.
<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/VFooter.gif" width="640" />

- **print** prop added to the **DocumentViewer component**. Set **showPrint** to true to enable printing of the documents added to the DocumentViewer.

- **allow** prop added to the **Frame component**. Specifies a **Permissions Policy** for the Frame component. The policy defines what features are available to the Frame (for example, access to the microphone, camera, battery, web-share, etc.) based on the origin of the request.
    > Examples:
    > allow="camera 'none'; microphone 'none'"
    > allow="fullscreen" --> When the video is opened in the Frame component, the fullScreen feature will be actived on the video.


 
 

### Features on Plateau Mobile

**iOS**

- **VProgressCircular** style improvements completed.
- **MarkerIcon feature** added to the Map component.
- **Encryption features; hash(), encrypt(), decrypt()** also completed for mobile.

**Android**

- **WebView** feature is on live, allowing you to display web content directly through the SDK.
- **Add New Font** feature added for mobile apps. Users will now be able to see the fonts they added on mobile.
- **Application Theme Development** is complete for mobile. Style themes such as the primary and secondary ones set in Studio can be used on mobile devices.
- **Encryption features**; **hash()** completed. Development of **encrypt()** and **decrypt()** with **RSA-OAEP** algorithm completed.
- **MarkerIcon feature** added to the Map component.



## ![](https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-studio-common/plateau-studio/bugs.svg) **Bug Fixes**

### Fixes on Plateau Studio & UI Editor

- The **Editors bar in Plateau Studio stabilized** by removing the unnecessary scrolling.

- The **color input field and color picker area were working independently of each other and incorrectly** when a new font and a new color was added to the theme settings, fixed.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/themesettings.gif" width="640" />

- The **name input field was losing focus** with each keypress when a new font was added to the theme settings, fixed.

- The issue when the theme is being used throughout Studio, solved.


- The issue of transmitting CSS information to the mobile page preview, resolved.

- The issue of page rendering in the Mobile Preview where multiple CSS files are used, fixed.

- When the theme is changed, the page will now be rendered again so that it can be displayed with the new theme.

- The VDataTable toggle-selection-all parameters interface revised.

### Fixes on Style Editor & Component Styles

Several style related issues fixed and features enhanced in this version release:

 - The bug where the color picker in the Style tab couldn't select colors, resolved.

 - **Correct classes applied for Style** Height/Max Height/Min Height values for input components.


 - Style adjustments below for Height/Max Height/Min Height made for Input Components.

    - **VTextField:** Adjusted height. Added max height and min-height.
    - **PhoneInput:** Added height, max height, min-height.
    - **VTextArea:** Adjusted height. Added max height and min-height.
    - **VSelect:** Added height, max height, min-height.
    - **VFileInput:** Adjusted height, max height, min-height. Fixed issue where attach icon would stay above.
    - **VCombobox:** Added height, max height, min-height.
    - **VInlineDatePicker:** Adjusted height, max height, min-height. Fixed issue where date icon would stay above.
    - **VInlineTimePicker:** Added height, max height, min-height.

 - The issue where the provided **margin** and **padding** values of the **VTimelineItem component** not working correctly, resolved.

 - The issue where the provided **padding** values of the **VAppBar component** not being reflected in the inner component, resolved.

 - The issue of **Vuetify CSS styles overridding** Shell applications CSS, fixed. 
  
 - The issue of **styled components** not reflecting the selected **theme colors**, resolved.

- The issue with **FontStyle** and **FontWeight** not working in the **header section of the VDataTable component**, fixed.

- The issue of **Active Step Label** not reflecting on the Web for the **VStepper** component, resolved.

<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/VStepperActiveStepLabel.gif" width="640" />

- The issue of **Active Color** not reflecting on the Web for the **VSelect** component, resolved.

 <img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/VSelectActiveColor.gif" width="640" />

- The issue where the **defaultBorderColor** of the **VRadio** component not reflecting on the Web, fixed.

- The issue of style values not working in runtime for mobile when it does not have default value, resolved.

- Changes made by the **DefaultTabsLabelLineHeight and ActiveTabLabelLineHeight props of the VTabs component** were not noticeable on the screen. To fix this, a prop called **tabsBarHeight** was opened and tabs were allowed to get the desired height value. In this way, the changes created by the lineheight values on the screen became visible.
<img src="https://stechq.github.io/cdn/release/notes/plateau-studio/plateau-web/release-notes/v1.11.0/tabsBarHeight.gif" width="640" />

- **Errormessage font-Color** prop also changes the label font-Color prop of the VSelect component, fixed.

- **BackgroundColor prop** changes the VBtn color instead of VBtnToggle, fixed.

- The issue of the **backGround value** being reverted to the default value when it is given and deleted, resolved.

- Logo selections removed from App Settings for the Mini applications.


### Enhancements on Components

- The **left-right Vuetify properties** for the **VTimelineItem** component reopened.

- The issue occurring in the **mobil** reflection of the **template** created for the **VAppBar** component, resolved.

- The issue of **MenuBoxShadow inset** prop of the **QPhoneInput, VInlineDatepicker, VAutocomplete,VCombobox** components not working, fixed.

- The issue where the **inset would appear and disappear when a new image was added to the src** of the VImg component instead of the default image, with the inset prop enabled, fixed.


- If there is more than one **Frame** component on the page, the problem that when **post() is made to a Frame component**, the page is opened in the last Frame component instead of the corresponding Frame has been solved.

- The issue of **Carousel component's showArrow prop** not working properly in mobile, resolved.


- **Backgroundcolor prop of the VStepper** component, removed. Designs continue to be made with VStepperHeader and VStepperContent backgroundcolor props.

- The following **props fixed on VStepper component:** 
  - Completed Step Label(Font Family-Style-Size-Weight-Color) props, Error Step Label (Font Family-Style-Size-Weight-Color) props.

- The following **props fixed on VInlineDatePicker component:** 
  - Menu Selected Date(Font Style-Weight) props, Menu Date Content (Font-Size) prop.

- **VNavigationDrawer's Box Shadow value** appeared in the source code but was not reflected on the screen, fixed.

- **Text props (Font Family-Style-Size-Weight) of the VListGroup** component fixed.



### Fixes on Plateau Mobile


**iOS**

- The issue where **the cursor would move to the end of the text** when trying to edit from any position in the TextField component, resolved. You can now edit text from any position within the TextField.

- The issue with **incorrect data being sent in the event of the QMap component**,fixed.


- The issue of **causing the VSlideGroup component to not scroll** due to Qvalue, fixed.


**Android**

- The problem of **x,y and blur props in VChipGroup not being reflecte**d on mobile, resolved.
- The problem of not giving border width to a **specific edge** fixed.
- If the **box shadow color contains alpha value**, the box shadow not visible. This problem fixed.
 