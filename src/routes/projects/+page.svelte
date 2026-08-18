<svelte:head>
	<title>Emilia McClure - Projects</title>
</svelte:head>

<h1 class="mb-6 border-b border-slate-700 pb-4 text-3xl font-bold">Projects</h1>

<div class="mb-4 border-b border-slate-700 pb-4">
	<div class="space-y-2">
		<div class="header">
			<div class="border-b border-slate-700 pb-4">
				<h2 class=" text-2xl font-bold" id="load-order-library">Load Order Library</h2>

				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>PHP</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>JavaScript</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>Python</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>Laravel</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>Bootstrap</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>Docker</span
				>
			</div>
		</div>
		<div class="body md:grid md:grid-cols-2 md:gap-3">
			<div class="mt-2 border-b border-slate-700">
				<h3 class="text-xl font-bold">Main Site</h3>
				<a
					class=" text-green-400 hover:text-green-500"
					href="https://github.com/phinocio/loadorderlibrary"
					target="_blank"
					rel="noopener noreferrer">GitHub Repo</a
				>
				|
				<a
					class=" text-green-400 hover:text-green-500"
					href="https://loadorderlibrary.com"
					target="_blank"
					rel="noopener noreferrer">Website</a
				>
				<p class="my-4">
					Load Order Library is a website I created to help with sharing modlist load orders for varying games
					like Skyrim and Fallout 4. The intention is to provide a convenient way for list users to get
					support, and for list authors to provide an easy view of what mods are in a given list. The website
					is created using PHP, Laravel Framework, JavaScript, Bootstrap, and other technologies. It is hosted
					on a Linux Server and makes use of Docker to containerize the application.
				</p>
				<!-- <img
					class="h-48 w-full self-center object-cover text-center md:h-full md:w-1/2"
					src="https://camo.githubusercontent.com/ee6ab8988ad79e6e3802e3a85aadea4b88c3ba50bc6723e5e8a8181c86472d16/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3537373731353233343735323433303038322f3831313736363138323835363039373830322f756e6b6e6f776e2e706e67"
					alt="Comparison page on Load Order Library"
				/> -->
			</div>
			<div class="mt-2 border-b border-slate-700">
				<h3 class="text-xl font-bold">API</h3>
				<a
					class=" text-green-400 hover:text-green-500"
					href="https://github.com/phinocio/loadorderlibrary"
					target="_blank"
					rel="noopener noreferrer">GitHub Repo</a
				>
				|
				<a
					class=" text-green-400 hover:text-green-500"
					href="https://docs.loadorderlibrary.com"
					target="_blank"
					rel="noopener noreferrer">API Documentation</a
				>
				<p class="my-4">
					A rewrite of the backend to be an API. This allows myself and 3rd parties to interact with the site
					via an API. I make use of this for the frontend rewrite, and the Mod Organizer 2 plugin.
				</p>
				<!-- <img
					class="h-48 w-full self-center object-cover text-center md:h-full md:w-1/2"
					src="https://camo.githubusercontent.com/ee6ab8988ad79e6e3802e3a85aadea4b88c3ba50bc6723e5e8a8181c86472d16/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3537373731353233343735323433303038322f3831313736363138323835363039373830322f756e6b6e6f776e2e706e67"
					alt="Comparison page on Load Order Library"
				/> -->
			</div>
			<div class="mt-2 border-b border-slate-700 md:border-0">
				<h3 class="text-xl font-bold">Frontend Rewrite</h3>
				<a
					class=" text-green-400 hover:text-green-500"
					href="https://github.com/load-order-library/frontend"
					target="_blank"
					rel="noopener noreferrer">GitHub Repo</a
				>
				<p class="my-4">
					Rewrite of the frontend to be Svelte. It was originally going to be React, but I decided to switch
					to Svelte instead. Still a work in progress.
				</p>
			</div>
			<div class="mt-2">
				<h3 class="text-xl font-bold">Mod Organizer 2 Plugin</h3>
				<a
					class=" text-green-400 hover:text-green-500"
					href="https://github.com/phinocio/loadorderlibrary-mo2-plugin"
					target="_blank"
					rel="noopener noreferrer">GitHub Repo</a
				>
				<p class="my-4">
					A plugin for Mod Organizer 2 allowing users to upload their modlists directly to the site from
					within MO2 itself.
				</p>
				<!-- <img
					class="h-48 w-full self-center object-cover text-center md:h-full md:w-1/2"
					src="https://camo.githubusercontent.com/ee6ab8988ad79e6e3802e3a85aadea4b88c3ba50bc6723e5e8a8181c86472d16/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3537373731353233343735323433303038322f3831313736363138323835363039373830322f756e6b6e6f776e2e706e67"
					alt="Comparison page on Load Order Library"
				/> -->
			</div>
		</div>
	</div>
</div>

<div class="mb-4 border-b border-slate-700 pb-4">
	<div class="space-y-2">
		<div class="header md:items-center">
			<div class="">
				<h2 class=" text-2xl font-bold" id="nazeem">Nazeem</h2>

				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>JavaScript</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>NodeJS</span
				>
				<span
					class="inline-flex items-center rounded-md bg-blue-700 px-2 py-1 text-xs font-medium text-blue-200 ring-1 ring-inset ring-blue-700/10"
					>Docker</span
				>
			</div>
			<a
				class=" text-green-400 hover:text-green-500"
				href="https://github.com/phinocio/nazeem"
				target="_blank"
				rel="noopener noreferrer">GitHub Repo</a
			>
		</div>
		<div class="body flex flex-col space-y-2">
			<p>
				Nazeem, named after the character from Skyrim, is a Discord bot I wrote for Dylan Perry's <a
					href="https://www.wildlandermod.com/"
					class="text-green-400"
					target="_blank"
					rel="noopener noreferrer">Wildlander</a
				> server. Its aim is to help with some basic moderation tasks and supply a couple for fun commands.
			</p>
			<h3 class="mb-4 text-xl font-bold">Features</h3>
			<ul class="list-decimal space-y-2 pl-4">
				<li>
					Gatekeep the server, making users type <span class="text-blue-400">/agree</span> to remove the role,
					granting them access to the rest of the server.
				</li>
				<li>
					Auto mute suspected bot/scam accounts. Based on a few keywords in a message, the bot will mute a
					user and then provide a notification in a log channel showing the suspected message.
				</li>
				<li>
					Allow people to give themselves a role by typing <span class="text-blue-400">/faction</span> then choosing
					from one of the Skyrim factions. Simply for fun.
				</li>
			</ul>
		</div>
	</div>
</div>
