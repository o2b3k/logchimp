<template>
	<div class="onboarding-content">
		<div class="onboarding-header">
			<h2 class="onboarding-heading">Create a new board</h2>
			<p class="onboarding-label">
				A board is a place where people can post and vote on ideas for a
				specific topic.
			</p>
		</div>
		<create-board class="onboarding-form" redirect="/dashboard" />
	</div>
</template>

<script>
// components
import CreateBoard from "../../components/board/CreateBoard";

export default {
	name: "OnboardingWelcome",
	components: {
		CreateBoard
	}
};
</script>
