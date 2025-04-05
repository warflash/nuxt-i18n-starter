<script lang="ts" setup></script>

<template>
	<div>
		<h1>Nuxt I18n Starter - {{ $t("hello") }}!</h1>
		<NuxtLinkLocale target="_blank" to="/my-page">
		Blank Link
		</NuxtLinkLocale>
		<NuxtLinkLocale to="/my-page">
		Default Link
		</NuxtLinkLocale>
	</div>
</template>
