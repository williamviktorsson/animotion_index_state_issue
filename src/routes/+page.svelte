<script lang="ts">
	import { Presentation, Slide, Transition } from '@animotion/core'


</script>

<Presentation options={{ history: true, transition: 'slide', controls: true, progress: true }} class="flex h-full items-center">
	<Slide animate>
		<ol>
			<Transition><li>example</li></Transition>
			<Transition><li>exampler</li></Transition>
			<Transition><li>examplest</li></Transition>
			<Transition><li>examplestest</li></Transition>
		</ol>
	</Slide>

	<Slide animate>
		<ol>
			<li class="fragment">working example</li>
			<li class="fragment">working exampler</li>
			<li class="fragment">working examplest</li>
			<li class="fragment">working examplestest</li>
		</ol>
	</Slide>
</Presentation>
