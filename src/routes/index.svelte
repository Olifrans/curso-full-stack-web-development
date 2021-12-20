
<script>
	import CursoItem from "$lib/curso-item.svelte";

	const title = "Curso Web Development Ful-Stack ";
</script>

<svelte:head> <title>{title}</title> </svelte:head>
<h1>{title}</h1>

<h2>Bem Vindo Ao Curso de Web Development Ful-Stack Com Svelt, Postgres, Vercel, e Gitpod</h2>
<form action="" method="">
	<input type="text" name="text" aria-label="Adcionar Curso" placeholder="+ adcione o curso desejado" />
</form>

<CursoItem />
<CursoItem />
<CursoItem />