<script context="module" lang="ts">
    import '../styles/tailwind-output.css'

    /**
     * This function runs before the component is created and runs both during 
     * server-side rendering and in the client. Used to fetch the categories from
     * firebase and have them loaded in the Navigation bar
     */
    export async function load() { return {} }
</script>

<slot />