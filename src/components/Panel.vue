<template>
	<div class="panel">
		<div class="header">
			<!-- For one way data binding in vuejs, we use textinterpolation. That's what the headline keyword in the brackets below does as a data object.-->
			<h2 class="headline">{{ headline }}</h2>
		</div>
		<div class="body">
			<!-- Using vue's slot element, which allows us to render child elements of our panel component within the body element. -->
			<slot />
		</div>
	</div>
</template>