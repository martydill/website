<template>
	<div>
		<h2>Hello</h2>
		<div>
			<a href="./blog/"><i class='nes-icon coin'></i>Blog</a>
		</div>
		<div>
			<a href="https://www.linkedin.com/in/martydill/"><i class='nes-icon linkedin'></i>LinkedIn</a>
		</div>
		<div>
			<a href="https://github.com/martydill"><i class='nes-icon github' />GitHub</a>
		</div>
		<div class="footer-container">
			<div class="footer">
				Made with <a href="https://nuxtjs.org/">NuxtJS</a> and <a
					href="https://github.com/jefer590/vuenes.css/">VueNES.css</a>
			</div>
		</div>
	</div>
</template>

<script></script>
import Vue from 'vue'
import VueNesCss from 'vuenes.css'

export default Vue.extend({
	name: 'HelloPage'
})
</script>
