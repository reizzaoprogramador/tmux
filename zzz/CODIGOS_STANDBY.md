
```
# Cópia e colar estilo Vim :TODO: NEM PRECISA MEU FISH tem atalhos pra copiar colar
set-window-option -g mode-keys vi
bind-key -T copy-mode-vi v send-keys -X begin-selection
bind-key -T copy-mode-vi C-v send-keys -X rectangle-toggle
bind-key -T copy-mode-vi y send-keys -X copy-selection-and-cancel
unbind -T copy-mode-vi MouseDragEnd1Pane
```


