This script can disable Devtool, help to secure your code While disabling DevTools can make it slightly more challenging for casual users to inspect and manipulate code

 *can also use the following link at last of html file*
 


 <a href="<script src="https://github.com/shashimehta03/disable-devloper-tools/blob/main/devmorescript.js"defer></script>" id="copy-link">Link Text</a>
<button onclick="copyToClipboard()">Copy</button>

<script>
    function copyToClipboard() {
        const linkElement = document.getElementById("copy-link");
        const linkText = linkElement.getAttribute("href");
        
        // Create a temporary input element
        const inputElement = document.createElement("input");
        inputElement.value = linkText;
        document.body.appendChild(inputElement);
        
        // Select and copy the link text
        inputElement.select();
        document.execCommand("copy");
        
        // Remove the temporary input element
        document.body.removeChild(inputElement);
        
        // Change the button text temporarily to indicate success
        const copyButton = document.querySelector("button");
        copyButton.innerText = "Copied!";
        setTimeout(function() {
            copyButton.innerText = "Copy";
        }, 2000);
    }
</script>


 (<script src="https://github.com/shashimehta03/disable-devloper-tools/blob/main/devmorescript.js"defer></script>)

  
  (<script src="https://github.com/shashimehta03/disable-devloper-tools/blob/main/devscript.js"defer></script>)




