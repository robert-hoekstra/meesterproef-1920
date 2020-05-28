<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
       About Strvct
      </h1>
      <h2 class="subtitle">
        Structured Vocabulary Creation Tool
      </h2>

<section>
    <h3 class="aboutHeading">What is Strvct?</h3>
    <p>Strvct is a tool designed by the Wallscope company located in Edinburgh. <br>
    
    The main goal of Strvct is to create a structured vocabulary from large amounts of data. Strvct does so by combining the power of linked data with great user interfaces.
    </p>

    <h3 class="aboutHeading">Linked Data</h3>
    <p>Linked data is something that's been here for a while. But a lot of companies don't really talk about it that they use this technology. Linked data is becoming more and more popular as more players get to know the full power. </p>

<p>
Linked data is possible because it displays the knowledge in a organization. The relation between data creates new data. Thus with linked data being displayed in a knowledge graph. One gets to see the full knowledge within an organization. This makes organizing and researching much easier.</p>

<p>Described by W3C:</p>

<blockquote>

	<p>
        The term LinkedData refers to a set of best practices for publishing structured data on the Web. These principles have been coined by Tim Berners-Lee in the design issue note LinkedData. The principles are:
    </p>
	
	<p>
        Use URIs as names for things Use HTTP URIs so that people can look up those names. When someone looks up a URI, provide useful information. Include links to other URIs. so that they can discover more things. The idea behind these principles is on the one hand side, to use standards for the representation and the access to data on the Web. On the other hand, the principles propagate to set hyperlinks between data from different sources.
    </p>
	<p>
        
        	These hyperlinks connect all LinkedData into a single global data graph, similar as the hyperlinks on the classic Web connect all HTML documents into a single global information space. Thus, LinkedData is to spreadsheets and databases what the Web of hypertext documents is to word processor files.
    </p>
</blockquote>

    
</section>

    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

h3 {
    padding: 0.5em;
}

p{
    text-align: left;
    padding-left: 1em;
    padding-right: 1em;
    min-width: 30em;
    max-width: 50em;
    padding-bottom: 1em;
}

blockquote{
    font-style: italic;
    margin-left: 1em;
    border-left: gray 0.5em solid;
}
</style>
