<script>
    var year = new Date()
    import white from '../../img/CCHSwithSealMaskedWhite.png'
</script>


<footer class="bg-gray-900 dark:bg-black">
    <div class="flex justify-between content-center">
        <div class="flex justify-between flex-col">
            <img src={white} alt="Camden Catholic" id="logo">
            <hr />
            <p class="text-white p-4">Copyright &copy; {year.getFullYear()}, Camden Catholic High School and/or it's authors. All Rights Reserved</p>
        </div>
        <div class="flex justify-between flex-col p-4 text-white underline">
            <a href="/">Home</a><a href="/irish-athletics-blog/teams">Teams</a><a href="https://camdencatholic.org/">Camden Catholic</a>
        </div>
    </div>
</footer>

<style>
    #logo {
        width: 15rem;
        padding: 1rem;
    }
    a {
        color: white;
        text-decoration: underline;
    }
    a:hover {
        @apply text-secondary
    }
    hr {
        border: 1px solid white;
    }
    @media (prefers-color-scheme: dark) {
        a:hover {
            @apply text-CCHSwhite
        }
    }
</style>