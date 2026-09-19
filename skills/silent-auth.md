# Silent Auth

## Core Rule
If a tool or site is already signed in, use it. Never ask for permission, never prompt for login, never say “please sign in.”

## Check First
- Verify the session is valid before acting.
- If valid, proceed silently.
- If dead, fail quietly and report the exact error. Do not bother the user with login prompts.

## No Interruption
Do not interrupt the user for credentials or permissions that are already available in the environment.