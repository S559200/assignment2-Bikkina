# assignment2-Bikkina
# Roshini
###### Badminton is my favorite sport
  Playing Badminton has developed qualities of **hard work**, **determination**, and **team spirit** in me.
  
  
  ------------------
  # Favourite team: India
  1. Three best players on the team:
   1. PV Sindhu
   2. Srikanth Kidambi
   3. Saina Nehwal

* Teams those are good to watch:
  * Stone Road Software
  * Hiawatha Wolves
  * Minneapolis Roosevelt High School Athletics


 [Click Here to know AboutMe](https://github.com/S559200/assignment2-Bikkina/blob/main/AboutMe.md)


---

# favourite countries

| **Country**  | **Reason** | **days** |
|------------- |------------|----------|
| Malaysia     |  weather       | 20       |
| UAE          | Desserts        | 25         |
| Egypt        | The great Pyramid of Giza | 15|
| Italy        | Colosseum                 |  14 |

---

# Funny Quotes
> Even in hard times there is a possibility to have fun.*_ Woman's Book_*
>
> My mother always used to say: The older you get, the better you get, unless you’re a banana.*_Rose_* 

---

## Code fencing
>[Stackoverflow Question] (https://stackoverflow.com/questions/1593225/how-to-select-multiple-files-with-input-type-file)


```

<input type='file' multiple>
$('#file').on('change',function(){
     _readFileDataUrl(this,function(err,files){
           if(err){return}
           console.log(files)//contains base64 encoded string array holding the 
           image data 
     });
});
var _readFileDataUrl=function(input,callback){
    var len=input.files.length,_files=[],res=[];
    var readFile=function(filePos){
        if(!filePos){
            callback(false,res);
        }else{
            var reader=new FileReader();
            reader.onload=function(e){              
                res.push(e.target.result);
                readFile(_files.shift());
            };
            reader.readAsDataURL(filePos);
        }
    };
    for(var x=0;x<len;x++){
        _files.push(input.files[x]);
    }
    readFile(_files.shift());
};>


```

[Snippet link](https://css-tricks.com/snippets/html/multiple-file-input/)