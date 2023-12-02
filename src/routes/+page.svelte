<script lang="ts">
    interface Person {
        name: string,
        age: number
    }

    let person : Person 
    person = {
        name: "Alina",
        age: 22,
    }
</script>

<h1>Welcome to SvelteKit</h1>
<div class="person">
    <p>{person.name} - {person.age}</p>
</div>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
