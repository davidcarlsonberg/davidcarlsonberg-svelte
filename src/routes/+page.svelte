<script>
    import jobs from '$lib/jobs';
</script>

<h1>David Carlson Berg</h1>
<h2>Engineering Manager | Staff Web Engineer</h2>

<ul>
    {#each jobs as job}
        <li>{job?.company} - {job?.title}</li>
    {/each}
</ul>
