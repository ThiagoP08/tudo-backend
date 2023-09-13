import java.sql.Connection;
import java.util.List;

import dao.Dao;
import dao.TarefaDAO;
import model.Tarefa;

public class App {

	public static void main(String[] args) {
		System.out.println(Dao.getStatusConexao());
		Connection conexao = Dao.getConexao();
		System.out.println(Dao.getStatusConexao());
		
		TarefaDAO dao = new TarefaDAO();
		List<Tarefa> lista = dao.listar();
		
		
		lista.forEach(tarefa -> System.out.println(tarefa.getDescricao()));

	}

}
