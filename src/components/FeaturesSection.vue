<template>	
	<section id="features-section">
		<div id="features-container" class="content-column">
			<div id="feature-pyrmining" class="feature">
				<div class="feature-image"></div>
				<h2>Virtual Deposit Rewards</h2>
				<p>You get additional ERC20 Tokens with your ETH when you sell your Bonds. This is for participating in project developments.</p>
			</div>
			<div id="feature-soulecules" class="feature">
				<div class="feature-image"></div>
				<h2>Flux Fee</h2>
				<p>True sustainability with a fee that fluctuates with the health of the community. Fueled on FOMO and comfy on FUD.</p>
			</div>
			<div id="feature-helixparticle" class="feature">
				<div class="feature-image"></div>
				<h2>Masternode Downline</h2>
				<p>Every masternode has a continuous downline. That means your affiliate's affiliates trickle up to you.</p>
			</div>
		</div>
	</section>
</template>

<style lang="scss" scoped>
.feature p{
	font-size:17px;
	line-height:23px;
}
#features-section{
	padding-top:60px;
	padding-bottom:30px;
	color:#343434;
}
#features-container{
	display:grid;
	grid-gap:30px;
	grid-template-columns:auto auto auto;
}
h2{margin:0;}
.feature-image{
	background-size:contain;
	background-position:center;
	background-repeat:no-repeat;
	margin:0 auto;
	width:100px;
	height:100px;
}
#features-section p{text-indent:30px;}
#features-section{
	background-image:url('../assets/inverted-deep-firey-space.png');
}
#feature-pyrmining .feature-image {
        background-image: url(data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzNjciIGhlaWdodD0iMjY3IiB2aWV3Qm94PSIwIDAgMjc1IDIwMCI+PHBhdGggZD0iTTE4OCA2YTIyMiAyMjIgMCAwIDAtMzAgMjhjLTIgMC03IDgtNyAxMGwtMSA2YTE2NiAxNjYgMCAwIDAtMTEgNDUgMjU3IDI1NyAwIDAgMSAyNC00NGw0IDMgNiAzIDYgM2ExODgyIDE4ODIgMCAwIDAgOTEgNTVjMiAwIDUtMyA1LTZhMjM3NSAyMzc1IDAgMCAwLTEwNi02N2MtMS0xIDAtNCA1LTExYTI4OSAyODkgMCAwIDEgMjMtMzBjMC0yLTMtMS0xMCA1eiIvPjxwYXRoIGQ9Ik04NiA4MWE3MzkgNzM5IDAgMCAwLTM4IDUxIDEwNzEgMTA3MSAwIDAgMS00MiA1NWwtNiAxMHYzaDMzbDMzLTEgNC0xN2E0ODYgNDg2IDAgMCAwIDE1LTQ5IDE2MjggMTYyOCAwIDAgMCAxNC00OWwzLTcgNiA5YTMyNyAzMjcgMCAwIDEgMTkgMjVsNyAxMSAxIDEgOSAxMGE2MTMgNjEzIDAgMCAwIDE3IDIzbDkgMTIgNiA4IDEwIDEzIDggMTFoNTV2LTNjMC0yLTItNS05LTE1bC0yMS0yNy0xNi0yMmExNTA1IDE1MDUgMCAwIDEtMzMtNDNoLTZsLTUgOC0xMSAxNS01IDctMTItMTZjLTE2LTIxLTE4LTI0LTE3LTI1LTEgMS0zLTEtNC0zLTUtNy04LTEwLTEwLTEwcy01IDQtMTQgMTV6bTMgMTJsLTUgMTUtNSAxN2ExODAxIDE4MDEgMCAwIDAtMTggNjNsLTIgNUgxMWwyLTMgNy05YTY3OTkgNjc5OSAwIDAgMCA3MS05NGwtMiA2em04NiAxNWw2IDhhMzE4NCAzMTg0IDAgMCAwIDQ3IDYzbDExIDE0aC0yMWMtMTYgMC0yMC0xLTIwLTJsLTEtMS01LTUtMjEtMjgtOS0xMi01LTYgMi03YTU1NCA1NTQgMCAwIDEgMTEtMzBsNSA2eiIvPjwvc3ZnPg==);
}
#feature-soulecules .feature-image {
        background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iNjM1LjAwMDAwMHB0IiBoZWlnaHQ9IjUwNS4wMDAwMDBwdCIgdmlld0JveD0iMCAwIDYzNS4wMDAwMDAgNTA1LjAwMDAwMCIKIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaWRZTWlkIG1lZXQiPgo8bWV0YWRhdGE+CkNyZWF0ZWQgYnkgcG90cmFjZSAxLjE1LCB3cml0dGVuIGJ5IFBldGVyIFNlbGluZ2VyIDIwMDEtMjAxNwo8L21ldGFkYXRhPgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCw1MDUuMDAwMDAwKSBzY2FsZSgwLjEwMDAwMCwtMC4xMDAwMDApIgpmaWxsPSIjMDAwMDAwIiBzdHJva2U9Im5vbmUiPgo8cGF0aCBkPSJNNDE4MCA0MjIwIGMtNzMgLTI3IC0xNDQgLTc3IC0yMTcgLTE1MyAtMTk0IC0yMDQgLTM0OCAtNTI4IC02MTgKLTEzMDIgbC05NyAtMjgwIC04NyAtMTAwIGMtMjc2IC0zMjAgLTQ5NiAtNDcyIC03NjggLTUzMSAtMTE1IC0yNSAtMzE0IC0yMwotNDE4IDUgLTE2NyA0NCAtMzI2IDE0NSAtNDU1IDI5MCAtOTEgMTAyIC0xNzQgMjIwIC0yOTcgNDI2IC0yMDcgMzQ3IC0zMjIKNTA1IC00NzkgNjU1IC0xMzQgMTI4IC0yNDYgMTk2IC0zODIgMjMxIC04NiAyMiAtMTQzIDI0IC0xNjAgNyAtMTkgLTE5IC0xNQotNzYgNSAtODYgMTAgLTUgNDcgLTEyIDgyIC0xNSA5NyAtOCAxOTYgLTYxIDI5MSAtMTU2IDE3MiAtMTcxIDI3OSAtMzg2IDU0MAotMTA4NiAyNDcgLTY2MyAzNzggLTkxNiA1NzUgLTExMTAgOTggLTk3IDE2NiAtMTQzIDI3MyAtMTgzIDU5IC0yMyA4MiAtMjYKMTk3IC0yNiAyMDQgLTEgMzAwIDQwIDQ2MCAxOTkgMjI4IDIyNSA0MTQgNTk3IDY5MSAxMzg1IGw1OCAxNjQgOTkgMTE5IGMyMDIKMjQzIDMzNCAzNjIgNDg4IDQ0MiAxMjQgNjQgMjIxIDg4IDM0OSA4OSAyMTEgMCAzODAgLTgxIDU1NiAtMjY2IDEyMSAtMTI3CjE3NyAtMjA5IDQ2OSAtNjg0IDIyOSAtMzcyIDQ3MiAtNjMyIDY2NCAtNzA5IDczIC0yOSAxNTcgLTQxIDE3NiAtMjUgMTggMTUKMjAgNzQgMyA4NyAtNyA2IC0zNiAxMyAtNjUgMTYgLTEzNyAxNSAtMjc0IDE0MCAtNDA3IDM3MCAtMTAwIDE3NCAtMTkwIDM4NQotNDIxIDk5MiAtMTYyIDQyNSAtMjg2IDY5MSAtNDA5IDg3OCAtNzMgMTExIC0yMDYgMjUyIC0yODIgMjk3IC0xMzIgODAgLTI5MwoxMDMgLTQxNCA2MHogbTI4MCAtMTEwIGMxNjggLTY2IDMxOSAtMjQwIDQ2NiAtNTM1IDM1IC03MSA1OSAtMTIxIDUyIC0xMTEgLTcKMTEgLTQ0IDY3IC04MiAxMjUgLTMwNyA0NjcgLTcyMCA1MjEgLTEwMjQgMTM0IC0zNCAtNDMgLTY5IC04NyAtNzggLTk4IC0yOAotMzYgNzcgMTU4IDEyNiAyMzAgOTUgMTQxIDE5NCAyMjggMzAyIDI2NyA2NiAyMyAxNjAgMTkgMjM4IC0xMnogbS02IC0yMTAKYzE5NSAtNjEgMzczIC0yNTkgNTU2IC02MjAgNzQgLTE0OCAxNzAgLTM1NiAxNzAgLTM2OSAwIC0zIC0zNCA1OSAtNzYgMTM5Ci0xODggMzYzIC0zOTIgNTg5IC01OTUgNjYwIC04MCAyNyAtMjIyIDM3IC0zMDIgMjAgLTMyIC02IC05NSAtMzAgLTEzOSAtNTIKLTExMCAtNTUgLTI1NCAtMTk4IC0zNTcgLTM1MyAtNDAgLTYwIC03NiAtMTEyIC03OSAtMTE1IC0yMCAtMTkgMTQzIDI3NiAyMDMKMzY1IDE5NSAyOTIgMzkxIDM5NSA2MTkgMzI1eiBtLTggLTIzNCBjMTgzIC00OSAzNjQgLTIxOSA1MzAgLTQ5OCA2MSAtMTA0CjIzNCAtNDQwIDIzNCAtNDU1IDAgLTUgLTMwIDQ0IC02NiAxMDcgLTIzMyA0MDggLTQzNiA2MDggLTY3NiA2NjUgLTgyIDE5Ci0yMjggMTkgLTMwMyAwIC03MyAtMTkgLTE2OSAtNjMgLTIzMiAtMTA2IC03MCAtNDggLTE4MyAtMTYwIC0yNTQgLTI1MCAtMzQKLTQzIC02NCAtNzkgLTY2IC03OSAtMTUgMCAxMjQgMjIyIDIwNiAzMjcgMTE2IDE1MCAyMzUgMjQ0IDM1NSAyODMgNzMgMjMgMTk5CjI2IDI3MiA2eiBtMjQgLTI0MiBjMjQyIC02OCA0NDIgLTI4NiA3MDAgLTc2NCAxMDUgLTE5NCAxMDUgLTE5NSAtMzEgMTQgLTIyOAozNTAgLTQyOSA1MjAgLTY3OCA1NzcgLTI1IDUgLTk1IDEwIC0xNTUgMTAgLTIzOCAtMSAtNDI3IC04OCAtNjQ5IC0zMDAgbC0xMDEKLTk2IDU1IDc5IGMzMCA0MyA5MCAxMjIgMTM0IDE3NCAyMjcgMjczIDQ3MyAzNzYgNzI1IDMwNnogbS0zMTg2IC0xMDUyIGMxOTgKLTMwNyAzODIgLTQ3MyA2MTQgLTU1MyBsOTcgLTM0IDE5NSAxIGMxODMgMCAyMDAgMSAyODUgMjcgMTgyIDU2IDMzOSAxNDggNTEwCjMwMSA4NyA3OCA4MiA2OCAtNDAgLTg0IC0yNTUgLTMxOSAtNTQyIC00NjQgLTg0NyAtNDMwIC0xNzEgMjAgLTMxMiA4OCAtNDUzCjIyMiAtMTM2IDEyOCAtMjUwIDI5NCAtMzg5IDU2MyAtNzMgMTQyIC03MiAxNDIgMjggLTEzeiBtMCAtMTU1IGMxMDYgLTE5NgoyNTQgLTM5MCAzNjYgLTQ4MiAxODEgLTE0OSAzMzMgLTIwMCA1NjUgLTE5MiAxNTUgNSAyMTcgMjEgMzUwIDg2IDE0OSA3NCAyMzgKMTUwIDQyOSAzNjYgMzcgNDEgLTY0IC0xMjIgLTEzMiAtMjE1IC03MiAtOTggLTIwMSAtMjMxIC0yNzggLTI4NiAtNzYgLTU0Ci0xNjkgLTk4IC0yNTQgLTEyMCAtOTEgLTIzIC0yNzAgLTE2IC0zNjAgMTUgLTIwOCA3MSAtMzk5IDI2MyAtNTczIDU3NiAtNTYKMTAwIC0xNzAgMzM1IC0xNjIgMzM1IDIgMCAyNCAtMzcgNDkgLTgzeiBtMTM2IC00MDIgYzIxMyAtMzQ4IDQ1OSAtNTE1IDc2MAotNTE1IDI2OSAwIDQ5NiAxMzggNzE4IDQzNSA0MSA1NSA3NyAxMDIgODAgMTA1IDMgMyAtMTQgLTMxIC0zOCAtNzUgLTE4MgotMzM4IC0zNjUgLTUzNCAtNTY3IC02MTIgLTkwIC0zNCAtMjM5IC00MyAtMzMzIC0xOSAtMjI5IDU4IC00MjAgMjQyIC02MDEKNTgwIC00NiA4NyAtMTY5IDM1MyAtMTY5IDM2NSAwIDMgMjQgLTM5IDU0IC05NCAyOSAtNTUgNzIgLTEzMSA5NiAtMTcweiBtMjE5Ci00OTcgYzE2NyAtMTgyIDM1NSAtMjY2IDU3MSAtMjU1IDExMSA1IDE5NCAzMCAyOTEgODcgODMgNDkgMjAwIDE1NyAyNzQgMjU1CjMyIDQxIDYwIDc1IDYyIDc1IDcgMCAtNTUgLTEwNiAtMTEzIC0xOTUgLTEzOCAtMjExIC0yODAgLTMyOSAtNDQ3IC0zNzIgLTExMQotMjggLTI1OCAtMSAtMzgzIDcyIC03MSA0MSAtMjIyIDE5NyAtMjg2IDI5NSAtNTUgODUgLTE2OCAyODkgLTE2OCAzMDUgMCA0CjMxIC0zOSA2OSAtOTYgMzggLTU3IDk2IC0xMzQgMTMwIC0xNzF6Ii8+CjwvZz4KPC9zdmc+Cg==);
}
#feature-helixparticle .feature-image {
        background-image: url(data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI0MDAiIGhlaWdodD0iNDAwIiB2aWV3Qm94PSIwIDAgMzAwIDMwMCI+PHBhdGggZD0iTTYxIDM0Yy01IDEtMTMgNS0xNiA3LTQgNC03IDktOCAxNmwtMSAzNGMtMSAyNy0xIDMwLTMgMzYtNCAxMC05IDEzLTI1IDE1SDB2MTZsNyAxYzE1IDAgMjIgNCAyNiAxNCAyIDYgMiA5IDMgMzkgMCAzMSAxIDMzIDMgMzcgNSAxMyAxNiAxOCAzNyAxOGgxMHYtMTZoLTljLTEzLTEtMTktNS0yMS0xNGwtMS0yNGMwLTQyLTMtNTMtMTctNjBsLTYtMyA2LTNjNy0zIDEyLTkgMTQtMTYgMi04IDMtMjMgMy00NGwxLTI0YzItMTAgOC0xMyAyMS0xNGg5VjMzSDc1bC0xNCAxek0yMTQgNDF2OGg5YzExIDEgMTcgMyAyMCA5IDEgNCAyIDcgMiAzNCAxIDM2IDIgNDIgOCA0OWwxMCA3IDQgM2MtMiAwLTkgNC0xMiA3LTggNy0xMCAxOC0xMCA1MGwtMSAyOGMtMiAxMS03IDE0LTIxIDE1aC05djE2aDE0YzEyLTEgMTQtMSAxOS0zIDctMyAxMS04IDE0LTE0IDItNSAyLTcgMy0zOCAxLTI5IDEtMzMgMy0zOCAzLTExIDExLTE1IDI2LTE1aDd2LTE3aC04Yy0xNi0xLTIxLTUtMjUtMTUtMi02LTItOC0zLTM4IDAtMjAtMS0zNC0yLTM2LTItNi03LTEyLTEzLTE1LTctNC0xNC01LTI2LTVoLTl2OHoiLz48cGF0aCBkPSJNNzggNzJ2MTNoMTl2MTQ0aDM4YzQ2IDAgNDIgMCA0NC0xIDIgMCAyIDEgMiA2djdoNDF2LTI2aC0xMGMtMTAgMC0xMCAwLTktMnYtMjVoLTMzdi0xMWgtNDB2MjVoNDB2LTExaDMwdjEwbDEgMTJjMCAyIDAgMi0xMCAyaC0xMHY2YzAgNiAwIDYtMyA2bC00MC0xaC0zOHYtMTdsLTEtMThoMTRjMTQgMCAxOC0xIDE0LTJsLTE1LTFoLTEydi0zMWgxM2wxNS0xYzMtMS0yLTItMTUtMmgtMTN2LTMwbC0xLTI5aDMwYzEtMi0yLTItMTUtMkg5OWwxLTR2LTRoMTlWNTlINzh2MTN6bTM2IDB2OEg4M1Y2NGgzMXY4em01MSAxMTh2N2gtMzB2LTE1aDMwdjh6bTUyIDM4djhoLTMxdi0xNmgzMXY4eiIvPjxwYXRoIGQ9Ik0xMzAgOTV2MTJoMTBsOS0xdjM3aC0xOXYyNWg0MHYtMTFoMzB2MTNsMSAxNWMyIDQgMy0zIDItMTd2LTE0aC0zM3YtMTFoLTE5di0yNGgzMHYxMmgxOXY5YzAgMTAgMSAxNCAzIDExdi0yMGgxOXYtMjZoLTQxdjEyaC0yOWwtMS01di01aDE5VjgyaC00MHYxM3ptMzUtMXY4aC0zMFY4N2gzMHY4em01MiAyNHY4aC0zMXYtMTZoMzF2OHptLTUyIDM4djdoLTMwdi03bC0xLThoMzF2OHoiLz48L3N2Zz4=);

}
@media only screen and (max-width: 780px) {
	#features-container{ grid-template-columns: auto; }
	.feature-image,h2{display:inline-block;}
	.feature-image{width:50px;height:50px;}
}
</style>


<script>

export default {
	name: 'Features',
	data: () => ({
		tab: 0
	}),
	methods	:{
		tabTo:function(to){
			this.tab = to;
		}
	}
}
</script>