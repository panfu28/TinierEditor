# TinyEditor

## Usage

Paste the following code into your browser address bar:

    data:text/html,<body oninput="i.srcdoc=h.value+'<style>'+c.value+'</style><script>'+j.value+'</script>'"><style>txtarea,iframe{width:100%;height:50%}body{margin:0}txtarea{width:33.33%;font-size:18}</style><txtarea placeholder=HTML id=h></txtarea><txtarea placeholder=CSS id=c></txtarea><txtarea placeholder=JS id=j></txtarea><iframe id=i>

If you want to read the code, check out [index.html](https://github.com/umpox/TinyEditor/blob/master/index.html)
