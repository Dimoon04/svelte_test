<script>
    export let name;
    const icons = [
        {
           name:'check-mark',
           path:'<path d="M21 10h-6.7l2.37 2.37a1 1 0 001.4 0L23 9.22V19a1 1 0 001 1h2a1 1 0 001-1V9.22l1.78 1.77a1 1 0 101.39-1.4l-3-2.99zm-18.17 1a1 1 0 011.4-1.38l3 3a1 1 0 001.36 1.37L12 10.88V20a1 1 0 01-2 0v-8.88l-2.83 2.82a1 1 0 11-1.41-1.42l3-3zM12 2a9 9 0 00-9 9h2a5 5 0 015-5v2a1 1 0 002 0V5a3 3 0 003-3a3 3 0 00-3-3H9a1 1 0 000 2h2a7 7 0 017-7z" fill="currentColor"></path>',    
        },
        {
            name:'delete',
            path:'<path d="M5.5 5.5A.5.5 0 0 1 6 6v6a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm2.5 0a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm2.5 0a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm2.5 0a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zM6.67 5.13 5.12 6.68 3.36 4.92 4.71 3.57 6.58 5.44 8.44 3.57 9.79 4.92 8.03 6.68Z" fill="currentColor"></path>'
        }
    ]
    let icon = icons.find((item) => item.name === name)
</script>