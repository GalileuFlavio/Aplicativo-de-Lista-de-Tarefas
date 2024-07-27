# Aplicativo-de-Lista-de-Tarefas
Descrição: Um aplicativo simples para gerenciar tarefas diárias.
// Tarefa.java
public class Tarefa {
    private String descricao;
    private boolean completa;

    public Tarefa(String descricao) {
        this.descricao = descricao;
        this.completa = false;
    }

    public void completar() {
        completa = true;
    }

    public boolean isCompleta() {
        return completa;
    }

    public String getDescricao() {
        return descricao;
    }
}
