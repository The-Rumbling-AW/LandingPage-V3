<script>
export default {
  name: "fans-section.component"
}
</script>

<template>

  <main>
    <h2>
      {{ $t('titulo_beneficios_fan_parte1') }}
      <span class="highlight">{{ $t('titulo_beneficios_fan_resaltado') }}</span>
      {{ $t('titulo_beneficios_fan_parte2') }}
    </h2>
<!-- Cards de beneficios para fans -->
    <section class="benefits">
      <div class="card">
        <div class="icon"><i class="fas fa-bell"></i></div>
        <p>
          {{ $t('beneficiofan1_parte1') }}
          <span class="highlight">{{ $t('beneficiofan1_resaltado') }}</span>,
          {{ $t('beneficiofan1_parte2') }}
        </p>
      </div>

      <div class="card purple">
        <div class="icon"><i class="fas fa-envelope"></i></div>
        <p>
          {{ $t('beneficiofan2_parte1') }}<br/>
          {{ $t('beneficiofan2_parte2') }}
        </p>
      </div>

      <div class="card">
        <div class="icon"><i class="fas fa-user-friends"></i></div>
        <p>
          {{ $t('beneficiofan3_parte1') }}<br/>
          <span class="highlight">{{ $t('beneficiofan3_resaltado') }}</span>
          {{ $t('beneficiofan3_parte2') }}
        </p>
      </div>

      <div class="card purple">
        <div class="icon"><i class="fas fa-map"></i></div>
        <p>
          {{ $t('beneficiofan4_parte1') }}<br/>
          {{ $t('beneficiofan4_parte2') }}
        </p>
      </div>
    </section>
  </main>
</template>


