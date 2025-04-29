<script>
    import jobs from '$lib/jobs';
</script>

<h1>David Carlson Berg</h1>
<p>Engineering Manager / Web Engineer</p>

<ul>
    {#each jobs as job}
        <li>{job?.company}</li>
    {/each}
</ul>
