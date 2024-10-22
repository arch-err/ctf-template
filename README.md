![logo](assets/logo.png)
{{ $values := (datasource "values") }}

# {{ $values.general.ctf.name }} 2024
{{- range $values.general.ctf.urls }}
- {{ . }}
{{- end }}

*{{ $values.general.ctf.description }}*

# Challenges
