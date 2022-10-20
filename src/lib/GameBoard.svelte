<div class="board flex flex-wrap mx-auto my-8">
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="1">X</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="2">X</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="3">X</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="4">O</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="5">X</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="6">O</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="6">X</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="7">O</div>
	<div class="text-4xl uppercase flex justify-center items-center rounded-lg" id="8">X</div>
</div>

<style>
	.board {
		width: 300px;
		height: 300px;
	}

	.board div {
		transition: 0.2s all ease-in-out;
		width: 90px;
		height: 90px;
		margin: 5px;
		background-color: #e2e8f0;
		font-family: 'Fredoka One', cursive;
	}

	.board div:hover {
		background-color: #94a3b8;
	}
</style>
