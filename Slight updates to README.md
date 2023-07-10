## Rivet branding components for IUL
### Lightweight set of assets adapted from IU's Rivet Design System to install up-to-date branding in IUL open source projects.

#### Installation
- Use "dist" components for plug-n-play HTML (more components will be added as needed)      
- Add relevant "css" file to your application's "head". This CSS uses a "rvt" prefix on classes and is designed so that it will NOT override any other application components.   

- Add Rivet javascript to your code (usually just before the closing "body" tag). Be sure to include 'Rivet.init' as shown. 
```  
  <script src="https://unpkg.com/rivet-core@2.4.0/js/rivet.min.js"></script>
  <script>Rivet.init();</script>
```
      
- For an interactive view of Rivet components, see the components library https://rivet.iu.edu/components/
- Header https://rivet.iu.edu/components/header/
- Footer https://rivet.iu.edu/components/footer/
- Card https://rivet.iu.edu/components/card/
- Tabs https://rivet.iu.edu/components/tabs/, includes tabs-specific js. 

#### Fonts
- UPDATE: each stylesheet includes IU spec fonts 

#### Build details using NPM 'rivet-source' SASS
NPM package at https://www.npmjs.com/package/rivet-core
```
// header.css compiled from  
@use 'defaults';  
@use 'header-system';  
@use 'grid';  
@use 'input-group'; 
@use 'utilities/display'; 

// footer.css compiled from  
@use 'defaults';
@use 'footer-system';   
@use 'grid';  
@use 'utilities/display';  

// card.css compiled from
@use 'card';
@use 'grid';

```

#### Source
- "src" is a clone of source files from the active Rivet repository https://github.com/indiana-university/rivet-source/ 