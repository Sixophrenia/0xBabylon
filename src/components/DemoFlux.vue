<template>	
	<div id="demo-flux" class="demo-calc">
		<div class="mathblock-division">
			<demo-calc-input label="ETH in Contract" placeholder="Contract ETH" v-bind:eqNum.sync="demoVariableA" ></demo-calc-input>
			<hr/>
			<demo-calc-input label="Total Invested ETH" placeholder="Imported ETH" v-bind:eqNum.sync="demoVariableB"></demo-calc-input>
		</div>
		<div class="eq-part"><div class="big-operator">=</div></div>
		<div class="eq-part">{{demoVariableA/demoVariableB*100}}%</div>
	</div>
</template>

<style lang="scss" scoped>
#demo-flux{text-indent:0;display:grid;grid-template-columns:auto auto auto;margin:0 auto;margin-top:40px;}
.mathblock-division{text-align:center; width:130px;}
.mathblock-division hr{border-width:1px;border-style:solid;}
.big-operator{font-size:25px;vertical-align:middle;}
</style>

<script>
export default {
	name: 'DemoFlux',
	
	data: () => ({
		demoVariableA: 3,
		demoVariableB: 4
	})
}
</script>