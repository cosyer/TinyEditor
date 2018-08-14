# TinyEditor

## Usage

Paste the following code into your browser address bar:

    data:text/html,<style>textarea,iframe{width:100%;height:50%}body{margin:0}textarea{width:33%;font-size:18}</style><body oninput="i.srcdoc=h.value+'<style>'+c.value+'</style><script>'+j.value+'<\/script>'"><textarea placeholder=HTML id=h></textarea><textarea placeholder=CSS id=c></textarea><textarea placeholder=JS id=j></textarea><iframe id=i>
    
If you want to read the code, check out [index.html](http://www.zweizhao.com/TinyEditor/)
