---
title       : Insert the chapter title here
description : Insert the chapter description here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf

--- type:NormalExercise lang:r xp:100 skills:1 key:5347fc2fc3
## Go solve this wallnut!

Word games are easy...unless they are in Spanish!

*** =instructions
-  Entero: Le haces esto a un cadáver 
-  Decapitado: Es lo que haces en un bote

*** =hint
- Hints are for the weak

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
#write answer to Entero in the form Entero="answer here, no caps" 
Entero=""
#write answer to Decapitado in the form Decapitado="answer here, no caps"
Decapitado=""
```

*** =solution
```{r}
#write answer to Entero in the form Entero="answer here, no caps" 
Entero="cremar"
#write answer to Decapitado in the form Decapitado="answer here, no caps"
Decapitado="remar"
```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki



test_object("Entero")
test_object("Decapitado")

test_error()

success_msg("Happy birthday little garbanzo!!")
```
