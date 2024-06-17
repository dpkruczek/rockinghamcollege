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
	.task-table {
		width: 100%;
		border-collapse: collapse;
		margin-top: 20px;
	}
	.task-table th, .task-table td {
		border: 1px solid #ddd;
		padding: 8px;
	}
	.task-table th {
		background-color: #f2f2f2;
		text-align: left;
	}
	.task-table td {
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
	<table class="task-table">
		<thead>
			<tr>
				<th>Task</th>
				<th>Description</th>
				<th>Grade</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Classical education</td>
				<td>Are you better than a bunch of nerds?</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Color vision</td>
				<td>Solve a rubic's cube</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Excursion</td>
				<td>Work together in a team</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Climbing</td>
				<td>Can you climb the academia ladder?</td>
				<td>PASS</td>
			</tr>
			<tr>
			<tr>
				<td>Building on time</td>
				<td>Assemble a unicorn</td>
				<td>FAIL</td>
			</tr>
			<tr>
				<td>Chug n' chuck</td>
				<td>Chug a beer and throw into barrel</td>
				<td>FAIL</td>
			</tr>
			<tr>
				<td>Finnish education</td>
				<td>What's the original song?</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Pop, play, prevail</td>
				<td>Destroy the balloons of your enemies</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Drink right</td>
				<td>Choose from 3 beers</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Crazy forehead</td>
				<td>Can you recognise the pattern?</td>
				<td>PASS</td>
			</tr>
			<tr>
				<td>Photographic memory test</td>
				<td>Can you draw something from memory?</td>
				<td>PASS</td>
			</tr>
		</tbody>
	</table>
	<p>More tasks will be posted</p>
</div>