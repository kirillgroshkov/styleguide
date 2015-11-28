
# HTML

## Use standard Meta Viewport

    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width">
  
## Use standard all-enabling (at least) CSP

    <meta name="Content-Security-Policy" content="default-src * 'unsafe-eval'; style-src 'self' 'unsafe-inline'; media-src *; script-src * 'self' 'unsafe-inline' 'unsafe-eval'">
    

## One-line breaks to split logical blocks

Always split 2 containers / rows / columns following each other with 1 empty line.

Don't split different items (e.g row following a container)


    /* avoid */
    <div class="container">
      <div class="row">
        <div class="col">
            Some content
        </div>
        <div class="col">
            Some content
        </div>
      </div>
      <div class="row">
        <div class="col">
            Some content
        </div>
        <div class="col">
            Some content
        </div>
      </div>
    </div>


    /* recommended */
    <div class="container">    
      <div class="row">      
        <div class="col">
            Some content
        </div>
        
        <div class="col">
            Some content
        </div>      
      </div>
      
      <div class="row">      
        <div class="col">
            Some content
        </div>
        
        <div class="col">
            Some content
        </div>        
      </div>      
    </div>

...

    
