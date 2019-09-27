<!--

author:   Markus
email:    
version:  1.0.0
language: de
narrator: Deutsch Female

script:   https://cdn.rawgit.com/davidedc/Algebrite/master/dist/algebrite.bundle-for-browser.js

script: https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

link: https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

@eval:    <script> Algebrite.run(`@input`) </script>


link:     https://pannellum.org/css/style.css
          https://cdn.pannellum.org/2.4/pannellum.css

script:   https://cdn.pannellum.org/2.4/pannellum.js

@panorama
<div id="panorama_@0" style="width: 100%; height: 400px;"></div>

<script>
  pannellum.viewer('panorama_@0', {
        "type": "equirectangular",
        "panorama": "@1",
        "autoLoad": true,
        "hotSpots": [@2]
  });
</script>
@end


@panorama_hotspots
<div id="panorama_@0" style="width: 100%; height: 400px;"></div>

<script>
  pannellum.viewer('panorama_@0', {
        "type": "equirectangular",
        "panorama": "@1",
        "hotSpotDebug": true,
        "autoLoad": true,
        "hotSpots": []
  });
</script>
@end


-->

# Testing liascript
This is just a short test to test a few liascript functions.

## Tests

My Question
  [[ ]] Option 1
  [[x]] Option 2
  [[ ]] Option 3

## Code


