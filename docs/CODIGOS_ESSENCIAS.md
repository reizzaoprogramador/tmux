# CODIGOS ESSENCIAIS 

> CODIGOS ESSENCIAIS PARA CHMAAR OS PLUGINS DO TMUX
```
# ==============================================================================
# @IMPORTANTE_PROFILE: Inicializacao e carregamento do TPM (Tmux Plugin Manager) : em tmux/tmux.conf
# ==============================================================================

# Lista de plugins (exemplo com os seus plugins atuais)
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-resurrect'
set -g @plugin 'tmux-plugins/tmux-continuum'

# Inicializa o TPM (ESTA LINHA DEVE SER SEMPRE A ÚLTIMA DO ARQUIVO TMUX.CONF)
run '~/.config/tmux/plugins/tpm/tpm'
```
