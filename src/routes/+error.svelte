<svelte:head>
    <title>Oops..!!</title>
</svelte:head>


<div class="content">
    <div class="message">
        <h1>404</h1>
        <p>That's not found</p>
    </div>
    <a href="/">Looking for Home?</a>
</div>

<style>
    .content {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100%;
        color: aliceblue;
        gap: 50px;
    }
    
    .message {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 10px;
    }

    h1 {
        font-size: 9rem;
        opacity: 0.15;
        font-family: 'thin';
    }

    p {
        font-size: 1.5rem;
        margin-bottom: -20px;
        position: absolute;
    }

    a{
        color: inherit;
    }
</style>