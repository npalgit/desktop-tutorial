# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.


https://stackblitz.com/edit/react-g7szzcvw-dckajjvk?file=App.jsx,style.css,index.js


import React, { useRef, useState } from 'react'
import Confetti from 'js-confetti'
import './style.css'


const App = () => {
var a = [{
  "name":"Amjad",
  "age":8,
  "country":"USA",
  "photo":"https://yt3.googleusercontent.com/dl8_J2aErJZzCr_g8mcyAnfhC0HOzwHTXDEs_IiUeCFoP80plxanBEZ4jhBvSPdxIIcOxtHi=s120-c-k-c0x00ffffff-no-rj"
},
{
  "name":"Aman",
  "age":40,
  "country":"USA",
  "photo":"https://yt3.googleusercontent.com/ytc/AIdro_mITNVKgcMi9xOlIPHIVyLaolvVUxR_A1Q-mQFtodbnPWc=s120-c-k-c0x00ffffff-no-rj"
},{
  "name":"Sara",
  "age":37,
  "country":"USA",
  "photo":"https://yt3.googleusercontent.com/aMbavNMR5QJAPEzXqMHOXdMbJVnlcle1tfnV4UKw4OKwHziTrU8LaRGH_lhIcxZhBkHtx1Rcnw=s120-c-k-c0x00ffffff-no-rj"
}]
  return (
    a.map(function(x) {
      return (<div>
      <img src={x.photo} alt="" />
      <h2>hello {x.name}</h2>
      <h2>Age {x.age}</h2>
      <h2>Country {x.country}</h2>
      <hr/>
      </div>);
    })



  )
}

export default App
