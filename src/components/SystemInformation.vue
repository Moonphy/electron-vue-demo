<template>
	<div class="box">
		<table class="table is-fullwidth">
			<thead>
				<tr>
					<th>Package</th>
					<th>Version</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Platform</td>
					<!-- <td>{{ platform }}</td> -->
				</tr>
			</tbody>
		</table>
	</div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
	data() {
		return {
			// platform: require('os').platform(),
		}
	},

	created() {},
})
</script>

<style></style>
