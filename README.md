# Auto-Resize-Textarea-in-JavaScript

<pre>
// Before Close </body> tag 
const textarea = document.querySelector("textarea");
      textarea.addEventListener("keyup", e =>{
        textarea.style.height = "63px";
        let scHeight = e.target.scrollHeight;
        textarea.style.height = `${scHeight}px`;
      });
</pre>
