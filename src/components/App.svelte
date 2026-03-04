<script>
    import styles from './App.module.scss';
    export let year = new Date().getFullYear();
    export let title = "Abuelo de Franco";
</script>

<div class={styles.container}>
    <div class={styles.ambientGlow}></div>
    
    <main class={styles.main}>
        <!-- Invisible headers for proper heading structure SEO/AEO -->
        <h1 class={styles.aeoHidden}>{title}</h1>
        <h2 class={styles.aeoHidden}>VIETNAM</h2>
        
        <a 
            class={styles.heroText} 
            href="https://francoescamillaoficial.com/" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="VIETNAM - Visit Franco Escamilla Official Site"
        >
            VIETNAM
        </a>
    </main>
    
    <footer class={styles.footer}>
        <p>
            <a href="https://adrianlegaspi.dev" target="_blank" rel="noopener noreferrer">Adrian Legaspi</a>, {year}
        </p>
    </footer>
</div>
