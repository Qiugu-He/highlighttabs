## Browser route tab
<img src="https://github.com/Qiugu-He/20-React-App/blob/master/03-Highlight_Tab/Tab.png" alt="alt text" width="100%" height="100%">

This small app let me practiced with
* react hook: useState
* react-router-dom: Router, NavLink, Routes, and Route
* Re-useable component: Tab

### File Structure:
```
src:
    - component:
        - Tab
        - Header
    - Page:
        - About
        - Features
        - Home
    - App.js
    - index.js
    - Routes.js
```

### Rendering flow:
```
-> App.js
    -> Header.js (Render each tabs with its NavLink)
        -> Tab.js 
    -> Routes
        (Switch looks through its children <Route> and render the first one that matches the current url )
        ->Switch 
            (page will be rendered based on url match)
            -> Route
```

## How to Run :
- npm install<br>
- npm run
- npm build (For production)
