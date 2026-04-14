# rohankapoorss.github.io
Hosted Samples


How it works:
  - yoursite.github.io/page.html?phone=919810012345 →
   redirects to https://wa.me/919810012345           
  - Only reads GET params (URL query string) — POST
  is inherently ignored since there's no form handler
  - Shows an error message if phone is missing       
  - Uses window.location.replace so the redirect page
   doesn't stay in browser history      
