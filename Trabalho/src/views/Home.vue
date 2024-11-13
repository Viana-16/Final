<template>
    <div>
      <FootbolForm />
    <h3>Noticias Principais</h3> 
    <main>
      <!-- Primeira reportagem(Card) -->
      <div class="report1">
        <div class="report1-card" id="card-1">
          
        </div>
        <div class="report1-card" id="card-2">
                <h2 class="report1-card-title">Copa do Brasil 2024 termina em título para o Flamengo</h2>
                O Flamengo saiu de Belo Horizonte com mais um título da Copa do Brasil e para sempre será lembrado no
                folclore do futebol pelo “batismo” da moderna Arena MRV. Até esse domingo, o estádio do Atlético-MG 
                nunca tinha celebrado a entrega de um troféu — e quis o destino que não fosse para o clube mineiro.
                Mas esse foi o menor dos problemas; a partida, que deveria ser apenas motivo de festa, teve confusão
                 antes, durante e depois de a bola rolar. E tanto do lado de dentro, quanto do lado de fora do estádio.
                
            </div>
      </div>
      <!-- Reportagens em linha -->
        <div class="reports">
          <div class="reports-card" id="card1">
            <h2 class="reports-card-title">Seleção Brasileira divulga numeração com novos donos para as camisas 9 e 10</h2>
          </div>
          <div class="reports-card" id="card2">
            <h2 class="reports-card-title">Arana sofre entorse no tornozelo direito e fica fora de treino da seleção brasileira; André também é poupado</h2>
          </div>  
          <div class="reports-card" id="card3">
            <h2 class="report1-card-title">Artilheiro do Brasileirão, Estevão analisa confronto contra a Venezuela</h2>
          </div>
          <div class="reports-card" id="card4">
            <h2 class="report1-card-title">Fenerbahçe busca a contratação de Anderson Talisca</h2>
          </div>

        </div>

    </main>
    
</div>
</template>

<script>
import FootbolForm from '@/components/FootbolForm.vue';

export default {
name:'Home',
components:{
  FootbolForm
}

}
</script>
