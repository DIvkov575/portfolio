<script>
    export let title = ""
    export let content = ""
    export let imageUrl = null;
    export let imageAlt = null;
</script>

<style>
    #post {
        border: 1px solid #dddddd;
        border-radius: 4.5px;
        margin-bottom: 1rem;
        padding: 1.5rem;
    }

    #w1 {
        display: flex;
        align-items: flex-start;
        height: 150px;

    }
    img {
        height: 100%;
        margin: 0 auto 0 auto;
    }
    h2 {
        text-decoration: underline;
        font-size: 1.3rem;
        margin-bottom: 0.5rem;
    }
    h3 {
        flex-grow: 1;
        font-size: 1rem;
    }

</style>

{#if imageUrl}
    <div id="post">
        <h2 class="title">{title}</h2>
        <div id="w1">
                <img src={imageUrl} alt={imageAlt}>
                <h3 style="margin-left: 1rem">{content}</h3>
        </div>
    </div>
{:else}
    <div id="post">
        <h2>{title}</h2>
        <h3>{content}</h3>
    </div>


{/if}

