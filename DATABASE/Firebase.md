# Fire Base Real time Database Connection



## Create Fire Base Account
-  [﻿firebase.google.com/](https://firebase.google.com/) 


## Now Create New Project and Follow the Steps
![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/abGQKYB1GRLGvS3N3ceVJ.png?ixlib=js-3.7.0 "image.png")

**STEP 1 :** 

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/PITDDuMw0rcy74iQKOO_t.png?ixlib=js-3.7.0 "image.png")

**STEP 2 :**

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/6X6j__OBwoaS9RmGXjK8a.png?ixlib=js-3.7.0 "image.png")

**STEP 3 :**

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/OzVViNpfRBJEtSAe8M7l2.png?ixlib=js-3.7.0 "image.png")

**STEP 4 :** CLICK ON REAL TIME DATABASE 

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/oYB3C358MP5cA1BMTfSBi.png?ixlib=js-3.7.0 "image.png")

 ** STEP 5 :**

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/z9_cuHYAncQKLE6nl-fGx.png?ixlib=js-3.7.0 "image.png")

**STEP 6 : CHOOSE NEAR LOCATION [ SINGAPORE ] **

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/K9vd8UXQo8PaO0d8MLhhB.png?ixlib=js-3.7.0 "image.png")

**STEP 7 :**

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/K1zdYilUBtOwEl4yfjL8B.png?ixlib=js-3.7.0 "image.png")

STEP 8 : CLICK **RULES **and **Change **the **Rules **to from False to True Now Click on **Publish**

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/FJl5HKfBg-79qPplSYq7A.png?ixlib=js-3.7.0 "image.png")

STEP 9 :

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/OLEFLQFb2eHMUayJuhRw1.png?ixlib=js-3.7.0 "image.png")

STEP 10 :

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/Ybz7ndAcB-eB8Mf709kdG.png?ixlib=js-3.7.0 "image.png")

STEP 11 :

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/rpWYRHazXry5nAGm0vgWd.png?ixlib=js-3.7.0 "image.png")

STEP 12 :

![image.png](https://eraser.imgix.net/workspaces/uEVd5VrIDmxwbXPR4Nv9/cW4TYXUmCph0yuFtGhfXbN9Xayl1/txh_-20-xEpn1AfrE20i_.png?ixlib=js-3.7.0 "image.png")



## NOW THE CONFIG FILE IS READY 
```
// Your web app's Firebase configuration
const firebaseConfig = {
 apiKey: "AIzaSyBu1GcvrWPRm7ou6yFZWpuzYn_HcWYFIP4",
 authDomain: "give-any-name-92d60.firebaseapp.com",
 databaseURL: "https://give-any-name-92d60-default-rtdb.asia-southeast1.firebasedatabase.app",
 projectId: "give-any-name-92d60",
 storageBucket: "give-any-name-92d60.appspot.com",
 messagingSenderId: "201914973518",
 appId: "1:201914973518:web:d191f8a799a65fd3cef21f"
};
**- SEE YOUR CONFIG FILE MAY BE DIFFERENT**
```
## **ADD THIS SDK IN HEAD TAG**
```
<!--FireBase SDK-->
<script defer src="https://www.gstatic.com/firebasejs/8.10.1/firebase.js"></script>
<script defer src="https://www.gstatic.com/firebasejs/8.10.1/firebase-auth.js"></script>
<script defer src="https://www.gstatic.com/firebasejs/8.10.1/firebase-firestore.js"></script>
```
## **Initialize Firebase**
```
firebase.initializeApp(firebaseConfig);

const db = firebase.database().ref("ReqForm");

db.push({
  name: name,
  email: email,
  message: message,
});
```
**IF WANT ONLY UNIQUE DATA **

```
// Initialize Firebase
firebase.initializeApp(firebaseConfig);

const db = firebase.database().ref("ReqForm");
 
var newRef = db.push();

newRef.set(
  {
    name : name,
    email : email,
    message : message
  }
);
```


