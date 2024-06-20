<template>
    <div>
        <h2>List of Albums</h2>
        <ul>
            <li v-for="album in albums" :key="album.id">{{ album.name }}</li>
        </ul>
    </div>
</template>