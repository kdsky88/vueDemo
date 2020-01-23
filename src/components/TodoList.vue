<style>
* { box-sizing: border-box;}
.headerB {
	background-color: #8482be; padding: 30px 30px;
	color: white; text-align: center;
}
.headerB:after {
	content: ""; display: table; clear: both;
}
</style>
<template>
	<div id="todolistapp">
		<div id="headerB" class="headerB">
			<h2>Todo List App</h2>
			<input-todo></input-todo>
		</div>
	<list></list>
	</div>
</template>
<script type="text/javascript">
import InputTodo from './inputTodo.vue';
import List from './List.vue';

export default {
	name : 'todo-list',
	components : { InputTodo, List}
}  
</script>
