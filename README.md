# Mutiple angular elements on same page
Working example of multiple angular elements on same page. Using ngx-build-plus, to avoid "Zone already loaded error"

# Build
Build "angular-element-a" and "angular-element-b" using "npm run build". <br>
It generates main.js in /dist folder respectively.

# Run
Consume "main.js" of each element in "test-angular-elements". <br>
Provide angular umd modules, zone and other dependencies globally. (For eg: /extern in test-angular-elements) <br>
"npm start" in "test-angular-elements", you should see both elements loaded on same page.
