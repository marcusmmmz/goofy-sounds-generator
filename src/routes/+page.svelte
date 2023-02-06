<script lang="ts">
	let sounds = {
		QmTqkZiwTVaheQTSNseJc3RJ4JuoU7dAvWRYXpvRJsmpPs: "AMOGUS.mp3",
		QmU7wTYbV8UfeUiHipudWMr5RwGVgeAAUweK1TE7pCzh2h:
			"Alarms, T-CAS and GPWS of Boeing 737.mp3",
		QmSH6vYktjsDx19fDTTnShX7EN9UyCXXXyxmGawjbqGb6X: "Alert sound effect.mp3",
		Qmbarm9nHB7mgNHjNUSwHcvRfyMKTZCgTQt95Tp2UeXTcS:
			"Among Us (Role Reveal) - Sound Effect (HD).mp3",
		QmQSypq1gnUey67x6M1ZjqdEvHP71U6D8EwBFbR1LtmouL:
			"Are You Dumb, Stupid, Or Dumb.mp3",
		QmXPj57ZVpAj3H1D4WuGZ2KGX8jqop872Jo7M3B8Fb7Z7o:
			"Back at it again at Krispy Kreme Vine.mp3",
		QmdHYv4vegdaxrTp2Vemkk1new2TWbDfNpecnEGiTPKPUN:
			"Bass Drop - Sound Effect (HD).mp3",
		QmaNyZr3svwXK3mBvwt3U6H7TQTq7Gv5jBVXxkqVBqFvRL: "Billy Vine.mp3",
		QmbskEYEsc1ipWfPgfFkwHphgz8gDqfrDs9CrTJ7riDiWn: "Boing sound effect..mp3",
		QmbVofHRBPjuB9xcbAsMazqtaLxYJCQ1BLJ21avZKmHSpz: "Bonk Sound Effect",
		QmPJzwCpZ5MYgNovs9LpPrjw2jnzCBpL5hGDCbf9T8KWnZ: "Brain fart.mp3",
		QmT7Hm8uTrFXD63iUabwukfm9ACWz6GAeWn8jMMJaRZ1vi: "Bruh Sound Effect.mp3",
		QmWi48z1EwXpW4CdNqUZMqUAdFBMjm3dTx1t91QUrWGsDp: "Bruh Sound Effect.mp3.sfk",
		QmPgVmdevoEDt1HeybnohKodurLohYLtTMb6HRgH7V9eKx:
			"Car Horn Honking (Sound Effect).mp3",
		QmT73ZWmuU5MCe3jCuS3NVcXVrUNZdzDamATssutTEBxoo:
			"Cartoon Bite SOUND EFFECT download.mp3",
		QmZhjEwNFHLifWCk74as2QJqeCCNg45X7T9UQ6Y2p4mDr8:
			"Cartoon Boing Sound Effect.mp3",
		QmaXrPRCBUrt3YPA4fr9ACtpxPFsYFPU3m28dCXHhdzNz8:
			"Cartoon Slip Sound Effect.mp3",
		QmaV77y5zZ3bn3oMKxUYFVhBRBthktBXCh7KKS2DsBrmvM:
			"Cartoon crazy run slip & crash sound effect.mp3",
		QmbxTtAb3j7MzCjhu3tLyxHQmYFd2WTMkXT2kvTroKAJga:
			"Ceritified Hood Classic Sound Effect.mp3",
		QmbTnu1Recncmuhede5KJ8oWJbjEi6dGH6ehmCExBqVyMS:
			"Chinese DOIT sound effect.mp3",
		QmT6pQiD7VeMBDyMKFBHTnmyFSb6sWZurLt4s8ZLZGdgU7:
			"Danger Alarm Meme Sound Effect.mp3",
		QmNgLfiYM8Bhy9WWNSfbryjLJwax8vm9b54LWHoV7ybSbn:
			"Discord leave sound effect.mp3",
		QmaE1txQPCrGBDU87FE9kyyKvvPyJ7iKzPizHYxpxXYxnM:
			"Duck Quack - Sound Effect (HD).mp3",
		QmasiuJeqXDqWjq919r97xdDEwcTUpjZBc3vu17nEhGsRY:
			"EAS Alarm and Beep TURN YOUR VOLUME DOWN.mp3",
		QmcFezeWUziJF83mk3xh7QcszzmqSTMU2RcXoBvS6qAKxJ:
			"Fart - Gaming Sound Effect (HD).mp3",
		QmPwQ2mhTa9FyRYYSmBpbcGtQmfqKqarShtp872zmb6HZv:
			"Fast Tip Toe Sound _ Sound Effects for Video (320 kb...",
		Qmf3HSQgtQDrguksiuKfwrELmJxptbje7u6WrvmzjoTuPm:
			"Flight whoa whoa whoa hey hey hey.mp3",
		QmRFo85XYHtsdQKGZYwZ36c8yi3hYsM1DbAHf398xyeg6b:
			"Fortnite Old Sound effects - Radio.mp3",
		QmNP6ioCAidEeS84ooi3e8d4mjXKqL2sRUv3nn3nzrgGWe:
			"Fortnite Radio Beep - Sound Effec.mp3",
		QmQEN6tBctothRKbp6a8HAkfobUtdo9QkfzxYgsEsZ8g82:
			"GTA San Andreas Mission Passed - Sound Effect (HD) (...",
		QmRPVu7w6vz6SbqzdoCpXfaNdyPz3rd2zfdJVDPLyWHfgn:
			"Gangstas Paradise Choir Sound Effect.mp3",
		QmSu83hosKhofEWuBMm2LXGnQ8D2CdWdrUZbLusXZLrmZm:
			"Gay Echo Voice TikTok Sound Effect.mp3",
		QmP95zstwrBc1BMscX8RUSzVr5cjWpevQRz3oFVuWiWAZh:
			"Go Crazy ahh Go stupid.mp3",
		QmVzXNJc4mfMrFMn7VJ8zUMmXBMGAVFYUDsmU7k5mTaT12: "Gold fish be like....mp3",
		QmYnrXp7WVA5Mynpb8gRZbwidFX6e3Ly2iinwovDEiUbcw: "HIS NAME IS JOHN CENA.mp3",
		QmXLLTbk14Dk6HkoiuQudd5xJMaMN5h28yavYy9LyC9DpL:
			"Hahaha Wtf Was That Sound Effect.mp3",
		QmYrUjdcYsgHYo7f639uVxL9yfukStNyw6gYLXjGcxtfgK: "Honk Sound Effect.mp3",
		QmUfuuEPiyXvRiFqhma8MxFGwJpkXb8faSRg6CVuuj7gYV: "I like ya cut G.mp3",
		// QmQ3vBn8yRnhP2SfarCi4kKnSPaUMCUC4AbmK86KbTbAgX:
		// "In the Jungle, the mighty jungle....mp3",
		QmaKUepQ4fcdUCVyzZa5XwRhapoKBMkLxXRGCrk2HQw7Mn:
			"JapaneseChinese Funny Scream - Sound Effect for Edit...",
		QmV7pNNusJkJbRgWAXJVfaptwMjyiPZUePt2YFjspjBXQr: "LETS GO sound effect.mp3",
		QmTMSrmRY4viQuAbKhFdWVyDVQPjvtapv2QQKpDycLqzhY:
			"Law & Order Sound Effect (HQ) [ Download Link].mp3",
		QmZ7c14RGzhxubp2mus8Rg7c5BMywNMrWmm1vY4zXsYr3u: "Me after spicy chip.mp3",
		QmXXeKfC6VmLBCC897FqAuaZMp2YANA6fdiJ86Avz3kT1a:
			"Mind the Gap London Underground - FREE AUDIO DOWNLOA...",
		QmXSFotbxn1q9eMQMhXHdiSihpNZMgm18YJWmgvqGs4pGs:
			"Minecraft Damage (Oof) - Sound Effect (HD).mp3",
		QmViscDv9c4hCVVLCmqxYxLvffEAjEMprNBwyhuZ95h9TR:
			"Minecraft Damage Sound Effect.mp3",
		QmTsatAS7PFTihmk1Dn6VzSHbnZfEds5rtAh4Ap6UhHRFF:
			"Monster inc sullivan meme.mp3",
		QmeaJyhjT2kk8MmutdShzZn9gPuHd98cZXRhEcwA3QeuTK:
			"Munch - Bite Sound Effect.mp3",
		QmUj8m7aqMr9TeYdFHsYB9ZQYERNhbhSLwcGrwf1rKdje3:
			"Non Copyright Fart sound Part 2 PP Technical .mp3",
		QmcetCcTLHRSC8M1cNYZ97vHUd45u4mpL1Mn8JCzpmWnC8:
			"Nope Sound effect (Dank Meme).mp3",
		QmQseD4d2nqoaiduXXY3XxPSj42i1cXzqyf5vdtR3JtpTD:
			"Oh my god SOUND EFFECT.mp3",
		QmWbCzGrKJvfBtDnbNcqRVxxfwVQr3qAKMzX5f5ZhmE265: "Original 21 meme.mp3",
		QmazzfJe8jyb5JvwLoPZEyGs91q1rWB9v1uYA7ctqnTaFf: "Our table ITS BROKEN.mp3",
		QmdGBKNiAYNDTNzU1R8yEMPv7yq72QpojFaC4ec4itXe2b:
			"Pitangus sulphuratus sound.mp3",
		QmTBnygVPx8ebaXcPaXB4gWPAXzwxZqVa8p9ygHkEtpQrn:
			"Pufferfish “AUGH” Sound effect.mp3",
		QmYtxofQjkkuUeY1cbskvbV11k12Zr71VUjnRxLjCbvCiC: "Punch Sound Effect..mp3",
		QmVhtzAGc7YMbHWTj6rphnJr8gtWjwiJe2jBQx43u24uH9:
			"Quick Fart Sound Effect.mp3",
		QmZYH8E84T2ZWBvN6xWjefD61WNjpBrQscjVyPn2tXkNxF:
			"Quick fart 2 (cartoon Sound effects).mp3",
		QmXa99tHZjWzZWomZUaJN6WoCTp6JBCstG91KhoMnzUyea:
			"Red bird Samsung notification.mp3",
		QmR1APkrpqVwNCovpa2DdCsaPSTwRCa1re83DRW9c9ADYj:
			"Robert Downey Jr Scream (ORIGINAL).mp3",
		QmNcyJVfeWnbZrwqjz5XgJhYiwhK2qksXQAUfpYuY4TqSY: "Ronaldo Siuu.mp3",
		QmdyJ46Jeaqhw4h7LXNzWvc3MfQ1NgmNVLdUiKTqdrhkU2: "SKIBBITY BOP MM DADA.mp3",
		QmaqfixgVxB73ACkfMVNicrHf6vbyD2P9bPh7eQtGcn8Mv:
			"Squidward walking sound effect.wav",
		QmfMiKUeuGoREzeu5fTeARtYfxfCSCtkFgc2P3z8bwFc2W: "Squish - Sound Effect.mp3",
		QmQDfFK29P5wQTuzPHgYpnVZEZnXuMwEGKy42zJVns3VZh:
			"Steven He - EMOTIONAL DAMAGE.mp3",
		QmXpDEWVAWnLiMoHGK6dtBHjUiUupDF1vXu91D94afbKoZ:
			"Taco Bell Bong - Sound Effect (HD).mp3",
		QmZBxSvkT4BWpfe4SBwNVA55QqsC5KkHf644wKZ2YZKgKw:
			"The Elder Scrolls IV - Oblivion Soundtrack - 04 Harv...",
		QmecxC1fLMgKSMydUinEsFJE9qBtKvwJgvht5ACCbUrYVK:
			"The Rap Battle (EVERY SUPA HOT RAPS).mp3",
		QmVFDJXPowSc59nxsm6WUKvmiLXbGHcwVCjcuwvYwiubfs:
			"They bugging bro, bro she made beans.mp3",
		QmS3JMYr2yaKHvpKrH9ErqCuJfKtckXdeq7RiMs91qdpcd:
			"Tiptoe Cartoon Sound effect.mp3",
		QmSwNHwGaXyyKJnU4Ai6Hjpx6Jt2EjjW8pBhueWCpTdaHZ: "Up-Down Sound Effect.mp3",
		QmXcexn7p4thpqcmtosFi2EaCpY6JCQReDjENyhLavQHcQ:
			"Vine Boom Sound Effect (Longer Verison For Real) (Re...",
		QmQNTkxTEQ5VWZEnUvdH3cpP4KCEMmMPgo2kHjxRjFgYrp:
			"WHOA Yankee with No brim (128kbps).mp3",
		Qma4i9DBk84BFjYMp4Ydo9PuwbQ2sQ9UgnYVxWsN1aZzwB:
			"Want A Break From The ADs.mp3",
		QmXH6HmbjNeHCLTto8zCirYjzL4a58KeDfYLo7qGSyp564:
			"What are you doing in my swamp HD (320 kbps).mp3",
		QmbeB4aPRVnrJ3J9iarqarycJPcz2ACxnSgaahsiGXNbCA:
			"What kind of MCdonalds has a message ..mp3",
		QmecN8Ya4mhZe1rc18xR7BtnLfdbVemW6wmryh7PJUdKsN:
			"What the dog doing Vine.mp3",
		Qmeh55h5EjYx1a5vdSzd5hEdsat4x33EDhzCdwbCMtfuV5:
			"Wilhelm Scream - Gaming Sound Effect (HD).mp3",
		QmT1SquwcbRGyKE6BFuWQ6T19gHJkHcfiLsn7Jj2rDBYgg:
			"WindowsXp error Sound Effect (HD DOWNLOAD).mp3",
		QmRrH9J1dp4yXdrsMWWESPeSJyZMomiLnF4ktVK3aKdMHC:
			"Woah nice c$@k sound effect",
		Qmbxrrx74nGdtvkpqL1uVEgEjyF2jHePZ3eNv17Y3nSxnZ:
			"Worst Beat Ever Made prod. @BBasedTJ.mp3",
		QmUZ7BUU8ojguKHqMgBuqmUW6oMLbNqA9gWq8nnJnh1vP1:
			"Yo this is the funniest shit I’ve ever seen in my li...",
		QmTYDNEARzvQ2W8zP8J6HzRXfjP66pLxaojhotGUZgZGTK:
			"You cannot use the Double Gulp cup for the Slurpee (...",
		Qmbuyyvu4H8nPaLXrY6bBmd8pL3ysxgBzNLgeLjg7A5x7W:
			"aEgh meme sound EFFECT.mp3",
		QmStB38evHHDtTE2fVcAZJAGcqSSG7reG1mUGzfg5eJJQT: "ayo the pizza here.mp3",
		QmW1bWaVUHYPB18D6aUgrPbeCk9VbLUYRDzRX5StS2BWVW: "bro what the hell boi.mp3",
		Qmd9Hmq5Xy65c1Hg1zKJ7k3FwBUHUL3LBgnF6AEhrBYso5:
			"cartoon RUNNING sound effect.mp3",
		QmSme29yKEwF3aCzncN49V3KJxfFTV3icKwMJJk29oHAFr:
			"deez Nuts sound effect DOWNLOAD (hd).mp3",
		QmZggqw5vLkN4pccUjW3RrHxcAztLiKb2hG4g3UhwR6M2E:
			"drip Goku meme Original song.mp3",
		Qmb62G1Ew7Qfm96cuWU284qCgMUCtNQnRRuopdTYWkjqsQ: "duh duh Skull Trumpet.mp3",
		QmarMdhNUzHiXtMxm98AyFrxp4H3rRC8oT1iAeZtFz4gBn:
			"googoo gaagaa i want milk.mp3",
		QmRkEKi3Jj2nzmfzygTzbuXigPyyCmRUf4cD5QNrssm1VT: "helikopter helikopter.mp3",
		QmSYp6QdLN6LbfxdCZAxzYgqLgXAz5hnHp5TGmraMGPUGv: "hyper BASS boost.mp3",
		QmNkR4pL6GhBYU4VAHDqsjEjMcaWRcETHmKkhXZyxtKpXi:
			"joel biden Joe biden old man.mp3",
		QmQW9SFxVxybukuJX1C5xMNydSh8RtbEfUuXPUrkNQP6do:
			"minecraft eating sound effect.mp3",
		QmX3eTGhjqQLyr3FZUGqGm9Fp3vdsqDSp1fL8GEynRYU2S:
			"my life be like meme sound effect.mp3",
		QmRHxiQGRQksj5pjheKHYzcngy6xMgVJWAt1yZmhi5SJ4t:
			"number 7 students watches MEME (free download) (128k...",
		QmVLgeEGgmdqZUy77Z8vzH4Cznycr313dSfUT1kvmmJaAW:
			"old Chinese man Singing the Chinese Rap.mp3",
		QmUXRfq8DrxGNq1zBZ8NhB3mdv3EbyK42FJVJX2zLRi33r:
			"one eye open when im sleeping full video.mp3",
		QmX32MTZ3LvFyk36HYPC48SYtHkzSvHnHAR5XbsViU2gqj:
			"oof oof oof ooooooooooooooooooffffffffffffffffff sou...",
		QmVDZXMwSLyKksVdfAdcKPYPNr6mFadEnnUcWsmwDZtnRn:
			"pet fart (hd sound Effect) 1.mp3",
		Qmf3nvoWiio3XwoMLP3uNycj96ShWFhAWdqDVk7gL79Lqp: "ph INTRO.mp3",
		QmZADpN4VnjpquUVBEuR7GkjVe6hL46Pa6dnMGcTpSidEC: "vine ukulele voice.mp3",
		QmXDqfQm7YZGKRGphpjWz2qQrKcwRj3z3Mrv5B7frwinQL: "Да ты чё.mp3",
	};

	let checkedSongs: boolean[] = [];
	Object.values(sounds).forEach((_, i) => (checkedSongs[i] = false));

	let audioTimers: Record<number, Timer> = {};

	let audioEls: HTMLAudioElement[] = [];

	function createTimer(duration: number, onTimeout: () => any) {
		let handle: NodeJS.Timeout | null = null;

		return {
			onTimeout,
			start() {
				handle = setTimeout(this.onTimeout, duration);
			},
			stop() {
				if (handle) clearTimeout(handle);
				handle = null;
			},
		};
	}
	type Timer = ReturnType<typeof createTimer>;

	function getRandomBounded(min: number, max: number) {
		return min + Math.random() * (max - min);
	}

	function onCheckedSong(i: number) {
		if (checkedSongs[i]) {
			let duration = getRandomBounded(min * 1000, max * 1000);

			audioTimers[i] = createTimer(duration, () => {
				audioEls[i].volume = volume / 100;
				audioEls[i].play();

				onCheckedSong(i); // restart timer
			});
			audioTimers[i].start();
		} else {
			audioTimers[i].stop();
			delete audioTimers[i];
		}
	}

	let min = 1;
	let max = 700;

	let volume = 30;
</script>

<img src="/banner.png" alt="banner" />

<div class="buttons">
	<button class="selected">goofy sounds</button>
	<button on:click={() => alert("not working yet")}>game sounds</button>
	<button on:click={() => alert("not working yet")}>brazilian sounds</button>
</div>

<ul>
	{#each Object.entries(sounds) as [cid, name], i}
		<li>
			<label>
				<input
					type="checkbox"
					value={checkedSongs[i]}
					on:click={async () => {
						checkedSongs[i] = !checkedSongs[i];

						onCheckedSong(i);
					}}
				/>
				{name}
			</label>
			<audio bind:this={audioEls[i]} src={"https://ipfs.io/ipfs/" + cid} />
		</li>
	{/each}
</ul>

<!-- <label>
	min
	<input type="text" bind:value={min} />
</label> -->
<label>
	max (less = higher goofy frequency)
	<input type="text" bind:value={max} />
</label>

<br />

<label>
	volume
	<input bind:value={volume} type="range" min="0" max="100" />
</label>

<br />

<button
	on:click={() => {
		checkedSongs = checkedSongs.map(() => true);
		checkedSongs.forEach((_, i) => onCheckedSong(i));
	}}>GOOF!!!!!!!</button
>

<style>
	:global(html, body) {
		margin: 0;
	}

	img {
		width: 100%;
	}

	.buttons {
		display: flex;
		justify-content: space-between;
	}

	.buttons button {
		width: 100%;
		background-color: inherit;
		border-color: #3894c4;
		border-style: solid;
		font-weight: bold;
		border-width: 3px 2px;
		/* cursor: pointer; */

		font-family: "BernhardGothicURW-Medium";
	}

	.buttons button.selected {
		background-color: #3894c4;
	}

	li {
		list-style-type: none;
	}

	ul li label {
		color: #d06d17;
		font-weight: 900;
	}

	@font-face {
		font-family: "BernhardGothicURW-Medium";
		src: url("BernhardGothicURW-Medium.eot");
		src: url("BernhardGothicURW-Medium.woff") format("woff"),
			url("BernhardGothicURW-Medium.otf") format("opentype"),
			url("BernhardGothicURW-Medium.svg#filename") format("svg");
	}
</style>
