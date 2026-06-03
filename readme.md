Banco == Firebase 
Linguagem dominante : HTML CSS JS . 




----------------------------------------------------------------------------------------------------
Acessos Firebase : 
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBrfXYmD0DwHD1Lk2Zf9c_Dvc3KrCiAD9A",
  authDomain: "almoco-empresa-7a582.firebaseapp.com",
  projectId: "almoco-empresa-7a582",
  storageBucket: "almoco-empresa-7a582.firebasestorage.app",
  messagingSenderId: "646365633884",
  appId: "1:646365633884:web:acd39ed091832d9ebdb599",
  measurementId: "G-BKJH0N2E6N"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

-----------------------X----------------------------------X-----------------------------------------
SDK Firebase : 
npm install firebase