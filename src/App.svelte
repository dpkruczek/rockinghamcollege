<script>
	let user = "Movitz";
  </script>
  
  <style>
	:global(body) {
	  font-family: 'Comic Sans MS', 'Arial', sans-serif;
      background-color: #ffccff; /* Light pink background */
      color: #000;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
	}
	.container {
	  width: 80%;
	  margin: 20px auto;
	  padding: 20px;
	  background-color: #ffff99; /* Light yellow background */
	  border: 5px dashed #ff6699; /* Pink dashed border */
	  box-shadow: 10px 10px 0 #ff6699; /* Pink shadow */
	}
	.header {
	  text-align: center;
	  margin-bottom: 20px;
	}
	.header h1 {
	  font-size: 2.5em;
	  margin: 0;
	  color: #ff3366; /* Bright pink */
	  text-shadow: 2px 2px 0 #33ccff; /* Light blue shadow */
	}
	.user-tab {
	  position: absolute;
	  top: 10px;
	  right: 10px;
	  padding: 10px;
	  background-color: #33ccff; /* Light blue background */
	  color: #fff;
	  border: 2px solid #ff3366; /* Bright pink border */
	  border-radius: 10px;
	  font-weight: bold;
	}
	.task-list {
	  list-style-type: square;
	  padding-left: 20px;
	  font-size: 1.2em;
	}
	.task-list li {
	  margin: 10px 0;
	  color: #3366ff; /* Bright blue */
	}
  </style>
  
  <div class="user-tab">
	Logged in as: {user}
  </div>
  
	<div class="container">
		<div class="header">
			<h1>Rockingham College application</h1>
		</div>
		<p>Welcome to the Rockingham College application page! You have been chosen to apply for our postdoc programme! Congratulations! In order to increase your chances you need to prove yourself. Here you will find a list of tasks that will help you increase your chances:</p>
		<ul class="task-list">
			<li>Task 1: Submit your previous research papers</li>
			<li>Task 2: Complete the online assessment</li>
			<li>Task 3: Provide letters of recommendation</li>
			<li>Task 4: Participate in an interview</li>
			<li>Task 5: Publish a new research article</li>
		</ul>
		</div>
  