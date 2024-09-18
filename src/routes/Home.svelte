<script lang="ts">
	import TodoCard from '../components/TodoCard.svelte'
	import AddButton from '../components/AddButton.svelte';
	import AddModal from '../components/AddModal.svelte';

	let showModal = false;

	const clickAddButton = () => {
		showModal = true;
	}

	const closeModalButton = () => {
		showModal = false;
	}
</script>

<div>
	<TodoCard mainText="test"/>
	<TodoCard mainText="한글 테스트"/>
	<TodoCard mainText="한글 테스트2"/>
	<!-- <AddButton handleClick={clickAddButton}/> -->
	<AddModal />
</div>
	
<style>
</style>