# e-jweb
<!DOCTYPE html>
<html lang="pt-br">
<head>
	<meta charset="utf-8">
	<title>Fromulario de Atualização cadastral</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="css/meucss.css">
  	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
</head>
<body>
	<div class="container-fluid  col-lg-8 col-lg-offset-2">
			<div class="text-center">
				<img class="img-fluid" src="imagens/IgrejaVerbodaVida.png">
			</div>
			<form action="processar.php" method="post">
				<div class="form-group">
					<label for="nome">Nome Completo</label>
					<input class="form-control" cltype="text" name="nome" id="nome">
				</div>
				<div class="form-group">
					<label for="mas">Masculino</label>
					<input class="" type="radio" name="masfem" id="mas" value="Masculino">
					<label for="fem">Feminino</label>
					<input class="" type="radio" name="masfem" id="fem" value="Feminino">
				</div>
				<div class="form-group">
					<div class="row">	
						<div class="col-6 col-sm-6">
							<label for="ins">Grau</label>
							<input class="form-control" type="text" name="instrucao" id="ins">
						</div>
						<div class="col-6 col-sm-6">
							<label for="forma">Formação</label>
							<input class="form-control" type="text" name="instrucao1" id="forma">
						</div>
					</div>
				</div>
				<div class="row">
					<div class="form-group col-3 col-xs-3">
						<label for="empre">Empresário</label>
						<input class="form-checkbox" type="checkbox" name="empresario" id="empre" value="sim">
					</div>
					<div class="form-group col-9 col-xs-9">
						<input class="form-control" type="text" name="pro" id="pro" placeholder="Profissão/Atividade">
					</div>
				</div>
				<div class="row">
					<div class="form-group col-4">
						<label for="cpf">CPF:</label>
						<input class="form-control" type="text" name="cpf" id="cpf" required="">
					</div>
					<div class="form-group col-4">
						<label for="rg">RG:</label>
						<input class="form-control" type="text" name="rg" id="rg" required="">
					</div>
					<div class="form-group col-4">
						<label for="ss">SSP:</label>
						<input class="form-control" type="text" name="ssp" id="ss" required="">
					</div>
				</div>

				<div class="row">
					<div class="col-6 form-group">
						<label for="nat">Naturalidade:</label>
						<input class="form-control" type="text" name="natu" id="nat">
					</div>
					<div class="col-6 form-group">
						<label for="nac">Nacionalidade:</label>
						<input class="form-control" type="text" name="naci" id="nac">
					</div>
				</div>

				<div class="row">
					<div class="col-6 form-group">
						<label for="data">Data de Nascimento:</label>
						<input class="form-control" type="date" name="dat" id="data">
					</div>
					<div class="col-6 form-group">
						<label for="civ">Estado civil:</label>
						<input class="form-control" type="text" name="civil" id="civ">
					</div>
				</div>
				<div class="form-group">
					<label for="conj">Se casado:</label>
					<input class="form-control" type="text" name="nomeconj" id="conj" placeholder="Nome do cônjuge">
				</div>
				<div class="row">
					<div class="col-6 form-group">
						<label  for="datcas">Data de casamento:&nbsp&nbsp&nbsp&nbsp&nbsp<input type="date" name="casamento" id="datcas"></label>
					</div>
					<div class="col-6 form-group">
						<label>O Cônjuge também é membro?:&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
						<label for="sim">Sim</label><input type="radio" name="simnao" id="sim" value="Sim">&nbsp&nbsp&nbsp&nbsp<label for="nao">Não</label><input type="radio" name="simnao" id="nao" value="Não"></label>
					</div>
				</div>
				<div class="form-group">
					<label for="end">Endereço:</label>
					<input class="form-control" type="text" name="endereco" id="end">
				</div>
				<div class="row">
					<div class="col-6 form-group">
						<label for="cid">Cidade:</label>
						<input class="form-control" type="text" name="cidade" id="cid">
					</div>
					<div class="col-6 form-group">
						<label for="barr">Bairro:</label>
						<input class="form-control" type="text" name="bairro" id="barr">
					</div>
				</div>
				<div class="row">
					<div class="col-6 form-group">
						<div class="form-group">
							<input class="form-control" type="number" name="numero" placeholder="Numero">
						</div>
						<div class="form-group">
							<input class="form-control" type="text" name="estado" placeholder="Estado/PB">
						</div>
					</div>
					
					<div class="col-6">
						<div class="form-group">
							<input class="form-control" type="text" name="pais" placeholder="Pais/Brasil">
						</div>
						<div class="form-group">
							<input class="form-control" type="text" name="cep" placeholder="Cep">
						</div>
					</div>
				</div>
				<div class="row">
					<div class="col-5 form-group">
						<div class="form-group">	
							<input class="form-control" type="tel" name="telefone1" placeholder="Telefone 1">
						</div>
						<div class="form-group">
							<input class="form-control" type="tel" name="telefone2" placeholder="Telefone 2">
						</div>
					</div>
					<div class="col-2 form-group">
						<div class="form-group">
							<label>
								Whatsapp	
								<input type="checkbox" name="whats1" value="telefonee1">
							</label>
						</div>
						<div class="form-group">
							<label>
								Whatsapp
								<input type="checkbox" name="whats2" value="telefonee2">
							</label>
						</div>
					</div>
					<div class="col-5 form-group">
						<div class="form-group">	
							<input class="form-control" type="text" name="op1" placeholder="Operadora">
						</div>
						<div class="form-group">
							<input class="form-control" type="text" name="op2" placeholder="Operadora">
						</div>
					</div>
				</div>
				<div class="form-group">
					<label for="email">E-mail:</label>
						<input class="form-control" type="email" name="email" id="email">	
				</div>
				<!-- Div para preencer os dependentes--> 
				<div class="row">
					<div class="col-6">
						<div class="form-group">
							<label for="dependente">Dependentes:</label>
							<input class="form-control" type="text" name="dependente" id="dependente" placeholder="Nome do dependente">
						</div>
						<div class="form-group">					
							<input class="form-control" type="text" name="dependente2" placeholder="Nome do dependente">
						</div>
					</div>
					<div class="col-6">
					<div class="form-group">
							<label for="datnvn">Data do novo nascimento:</label>
							<input class="form-control" type="date" name="datanovo" id="datnvn">
					</div>
						<div class="form-group">
							<input class="form-control" type="date" name="datanovo2" id="datnvn2">
						</div>
					</div>
				</div>
				<div class="row">
				<div class="col-6">
					<div class="form-group">
						<strong>Rhema:</strong>&nbsp&nbsp
						<label for="ja">
							Já Fez?
							<input type="radio" name="jafez" id="ja" value="Já fez">&nbsp&nbsp
						</label>
						<label for="jan">
							Ainda não Fez?
							<input type="radio" name="jafez" id="jan" value="Não fez">&nbsp&nbsp
						</label>
					</div>
					<div class="form-group">
						<strong>EMR:</strong>&nbsp&nbsp
						<label for="ja1">
							Já Fez?
							<input type="radio" name="jafez1" id="ja1" value="Já fez">&nbsp&nbsp
						</label>
						<label for="jan1">
							Ainda não Fez?
							<input type="radio" name="jafez1" id="jan1" value="Não fez">&nbsp&nbsp
						</label>
					</div>
					<div class="form-group">
						<strong>ERMM:</strong>&nbsp&nbsp
						<label for="ja2">
							Já Fez?
							<input type="radio" name="jafez2" id="ja2" value="Já fez">&nbsp&nbsp
						</label>
						<label for="jan2">
							Ainda não Fez?
							<input type="radio" name="jafez2" id="jan2" value="Não fez">&nbsp&nbsp
						</label>
					</div>
					</div>
				<div class="col-6">
					<br><label for="dnn"><strong>Data do seu novo nascimento:</strong></label>
					<input class="form-control" type="date" name="datanovonasc" id="dnn">
				</div>
				</div>
              	<div class="form-group">
					Já recebeu batismo no Espirito santo?:&nbsp&nbsp&nbsp&nbsp
					<label for="sim1">Sim</label>
					<input type="radio" name="sim1" id="sim1" value="Sim">&nbsp&nbsp&nbsp
					<label for="nao1">Não</label>
					<input type="radio" name="sim1" id="nao1" value="Não">
				</div>
				<div class="form-group">
                  <strong>Já fez Discipulado?</strong>:&nbsp&nbsp&nbsp&nbsp
					<label for="sim4">Sim</label>
					<input type="radio" name="sim3" id="sim4" value="Sim">&nbsp&nbsp&nbsp
					<label for="nao4">Não</label>
					<input type="radio" name="sim3" id="nao4" value="Não">
				</div>
				<div class="form-group">
					Batismo nas Águas:
					<label for="sim2">Sim</label>
					<input type="radio" name="sim2" id="sim2" value="Sim">&nbsp&nbsp&nbsp
					<label for="nao2">Não</label>
					<input type="radio" name="sim2" id="nao2" value="Não">
					&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
					<label for="asp">Aspersão</label>
					<input type="radio" name="asp" id="asp" value="Aspersão">&nbsp&nbsp&nbsp
					<label for="ime">Imersão</label>
					<input type="radio" name="asp" id="ime" value="Imersão"> 
				</div>
              
				<div class="row">
					<div class="col-6 form-group">
						<label for="face">Facebook:
						<input class="form-control" type="text" name="face" id="face" size="">
						</label>
					</div>
					<div class="col-6 form-group">
						<label for="insta">Instagram:
						<input class="form-control" type="text" name="insta" id="insta" size="">
						</label>
					</div>
				</div>
				<div class="form-group">
					<textarea name="intere" class="form-control">Observações
					</textarea>
				</div>
				
				<div class="form-group">
					<textarea name="intere1" class="form-control">Descreva seus interesses ou Robs
					</textarea>
				</div>
				<div class="form-group">
					<input class="btn btn-success" type="submit" name="enviar" id="enviar" value="Enviar">
				</div>					
			</form>
	</div>
</body>
</html>
