/* Add your CSS styles here */

body{
  /* change the background color */
  background-color: black;
  /* change the text color */
  color: white;
}

header{
  text-align: center;
}

/* flex layout here */
main{
  display: flex;
  justify-content: space-evenly;
}

section{
  /*  change the border width and color  */
  border: 3px solid green;
  /*  adjust the padding to work better with your content  */
  padding: 40px;
  /*  change the background color  */
  background-color: blue;
/*  remove if you do not want rounded corners  */
  border-radius: 10px;
}


@media screen and (max-width: 600px) {
  /* Styles applied when the viewport width is 600 pixels or less */
  main{
    flex-direction: column;
  }
  
  section + section{
    margin-top: 20px;
  }
}
