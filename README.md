![logo](assets/logo.png)
{{ $values := (datasource "values") }}

# {{ $values.general.ctf.name }} 2024
{{- range $values.general.ctf.urls }}
- {{ . }}
{{- end }}

## Description
*{{ $values.general.ctf.description }}*

# Results
**Username:**
**Team:**

![ ](assets/scoreboard.png)
![ ](assets/team-score.png)

# Challenges
