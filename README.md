# Rivet branding components for IUL

### Lightweight set of assets adapted from IU's Rivet Design System       
### Install up-to-date branding in IUL open source projects.

#### Installation
- Use "dist" components (e.g., header, footer) for plug-n-play HTML (more components will be added as needed)      
- Add "dist/rivet-iu.css" file to your application's "head". This CSS should not override any other application components.   
- Add Rivet javascript to your code (usually just before the closing "body" tag). 
```  
  <script src="https://unpkg.com/rivet-core@2.0.0-beta/js/rivet.min.js"></script>
  <script>Rivet.init();</script>
```       

#### Source
- "src" contains cherry-picked components in "raw" form from https://github.com/indiana-university/rivet-source/ 