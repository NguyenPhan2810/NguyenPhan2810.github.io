Please add the script to index.html

<script type="module">
      // Import the functions you need from the SDKs you need
      import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.1/firebase-app.js";
      import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.6.1/firebase-analytics.js";
      import { getDatabase } from "firebase/database";
      // TODO: Add SDKs for Firebase products that you want to use
      // https://firebase.google.com/docs/web/setup#available-libraries

      // Your web app's Firebase configuration
      // For Firebase JS SDK v7.20.0 and later, measurementId is optional
      const firebaseConfig = {
        apiKey: "AIzaSyA6nONsw0EXIWCZLEVs2UVNEfv3ek04ezg",
        authDomain: "panoramabds.firebaseapp.com",
        databaseURL: "https://panoramabds-default-rtdb.asia-southeast1.firebasedatabase.app",
        projectId: "panoramabds",
        storageBucket: "panoramabds.appspot.com",
        messagingSenderId: "124191299085",
        appId: "1:124191299085:web:9fb620d7ad0c53bd286744",
        measurementId: "G-RRLDGPKP8V"
      };

      // Initialize Firebase
      const app = initializeApp(firebaseConfig);
      const analytics = getAnalytics(app);
      // Get a reference to the database service
      const database = getDatabase(app);

</script>