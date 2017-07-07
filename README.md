# Memrise Answerer
A robot to automatically answer [Memrise](http://memrise.com) questions for you. Created to "aid" me in Science homeworks. To use simply just open up your JavaScript console and inject the script into the website like so:

    var script=document.createElement("script");script.src="https://cdn.rawgit.com/aeroniemi/memrise-answerer/b64da16e/memrise.js",script.type="text/javascript",document.getElementsByTagName("head")[0].appendChild(script);

Which is simply just a compressed way of inserting the following `script` tag into the header:

    <script src="https://cdn.rawgit.com/aeroniemi/memrise-answerer/b64da16e/memrise.js" type="text/javascript"></script>

Memrise decided to provide us will all the answers preloaded in the JavaScript rather than checking the answers server side so I decided to take advantage of that to answer the questions automatically for me, which is much more fun than answering homework questions manually.
