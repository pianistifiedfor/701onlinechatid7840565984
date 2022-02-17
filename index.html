<script type="module">
    // Import the functions you need from the SDKs you need
    import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.6/firebase-app.js";
    // Include firebase database
    import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.6/firebase-database.js";
    // TODO: Add SDKs for Firebase products that you want to use
    // https://firebase.google.com/docs/web/setup#available-libraries
  
    // Your web app's Firebase configuration
    const firebaseConfig = {
      apiKey: "AIzaSyABmBg-H_V0sm23iFnpcWkGqIsZFTVYvag",
      authDomain: "openchatroom7a.firebaseapp.com",
      projectId: "openchatroom7a",
      storageBucket: "openchatroom7a.appspot.com",
      messagingSenderId: "780437641834",
      appId: "1:780437641834:web:4d0b50732e9404f6570813"
    };
  
    // Initialize Firebase
    const app = initializeApp(firebaseConfig);
  
    var myName = prompt("Enter your name");

    function sendMessage() {

        var message = document.getElementById("messaage").value;

        firebase.database().ref("messages").push().set({
          "sender": myName,
          "message": message
        });

        return false;
    }

      firebase.database().ref("messages").on("child_added", function (snapshot){
        var html = "";
        html += "<li id='message-" + snapshot.key + "'>";
          // show delete button if message is sent by me
          if (snapshot.val().sender == myName) {
            html += "<button data-id='" + snapshot.key + "' onclick='deleteMessage(this);'>";
              html += Delete;
            html += "</button>";
          }
          html += snapshot.val().sender + ": " + snapshot.val().message;
        html += "</li>";

        document.getElementById("messages").innerHTML += html;

      });

      function deleteMessage(self) {
        // get message ID
        var messageID = self.getAttribute("data-id");

        //delete message
        firebase.database().ref("messages").child(messageId).remove();
      }

        // attach listener for delete message
        firebase.database().ref("messages").on("child_removed", function (snapshot) {
          // remove message node
          document.getElementById("message-" + snapshot.key).innerHTML = "This message was deleted";
        });
  </script>

    <form onsubmit="return sendMessage();">
        <input id="messaage" placeholder="Enter Message" autocomplete="off">

        <input type="submit">
    </form>
    <ul id="messages">
    </ul>