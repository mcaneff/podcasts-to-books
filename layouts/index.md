{{ define "main" }}
<h1>Books Mentioned in Podcasts</h1>
{{ range .Site.RegularPages }}
  <article>
    <h2><a href="{{ .RelPermalink }}">{{ .Title }}</a></h2>
    <p>{{ .Summary }}</p>
  </article>
{{ end }}
{{ end }}
