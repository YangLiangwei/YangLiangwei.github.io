---
title: "All Experiences"
type: "experience"
---

## All Experiences

{{ range .Site.Params.experience }}
  <div class="row experience">
    <div class="col py-2">
      <div class="card">
        <div class="card-body">
          {{- if .company_logo}}
          {{- $svg_icon := resources.Get (printf "media/icons/brands/%s.svg" .company_logo) -}}
          <div class="d-flex align-content-start">
            <div class="mr-2 mb-2">
              <img src="{{ $svg_icon.RelPermalink }}" width="56" height="56" alt="{{.company | plainify}}" loading="lazy">
            </div>
            <div>
          {{ end }}
          <div class="section-subheading card-title exp-title text-muted my-0">{{.title | markdownify | emojify}}</div>
          <div class="section-subheading card-title exp-company text-muted my-0">{{.company}}</div>
          <div class="text-muted exp-meta">
            {{ (time .date_start) | time.Format "January 2006" }} – 
            {{ if .date_end }}
              {{ (time .date_end) | time.Format "January 2006" }}
            {{ else }}
              Present
            {{ end }}
          </div>
          {{ with .description }}<div class="card-text">{{. | markdownify | emojify}}</div>{{end}}
        </div>
      </div>
    </div>
  </div>
{{ end }}
