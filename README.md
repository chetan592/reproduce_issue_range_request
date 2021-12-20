# reproduce_issue_range_request
Reproduce range request issue with ngx-extended-pdf-viewer in Angular and Node as a server.  

Steps to reproduce issue 

Angular - 

  npm install 
  
  ng serve

*ngx-extended-pdf-viewer is addded to project and url is passed to [src]

Node server - 

  Add pdf file to node folder 
  
  change name of your pdf file in index.js at line `const samplePDF = "./demo.pdf";`
  
  Run node index.js
  
 Try it on browser to check... 
  

