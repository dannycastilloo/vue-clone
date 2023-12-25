<script>

export default {
    name: 'Search'
}

</script>

<template>
    <button class="search-button">
        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-search" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M10 10m-7 0a7 7 0 1 0 14 0a7 7 0 1 0 -14 0" /><path d="M21 21l-6 -6" /></svg>
        <span>Search</span>
        <kbd>
            CTRL K
        </kbd>
    </button>
</template>

<style>

.search-button {
    border: none;
    background-color: transparent;
    color: #979797;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    font-weight: 500;
    cursor: pointer;
    font-size: 13px;
}

.search-button > kbd {
    border-radius: 4px;
    border: 1px solid #979797;
    padding: 5px;
    font-size: 8px;
    font-weight: 400;
}

.search-button:hover {
    color: #E1E1E1;
    transition: all .3s ease;
}

.search-button:hover > kbd {
    color: #4CAF50;
    border: 1px solid #4CAF50;
    transition: all .3s ease;
}

</style>