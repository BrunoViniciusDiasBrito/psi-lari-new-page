<template>
  <section id="sobre-mim" class="cta-one">
    <img
      src="/assets/images/shapes/cta-1-shape-1.png"
      class="cta-one__bg-shape-1"
      alt=""
    />
    <img
      src="/assets/images/shapes/cta-1-shape-2.png"
      class="cta-one__bg-shape-2"
      alt=""
    />
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="cat_one_moc wow fadeInUp" data-wow-duration="1500ms">
            <div
              class="cat_one_moc-bg"
              style="background-image: url(/assets/images/shapes/cta-1-shape-3.png)"
            ></div>
            <img src="/assets/images/profile-img.png" alt="Cat-1-Moc-1 Image" />
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="cat_one_content">
            <div class="block-title">
              <p>Um pouco sobre mim</p>
              <h3>Larissa Caroline<br />Benedito</h3>
            </div>
            <div class="cat_one_icon-wrap">
              <div class="cta-one__icon-single">
                <div class="cta-one__icon">
                  <i class="piloz-devices"></i>
                </div>
                <h3>
                  A Minha Missão
                </h3>
              </div>
            </div>
            <div class="cta-one__text">
              <p>
                A minha missão como Psicóloga tem como meta ajudar as pessoas
                por mim atendidas a entrarem em contato consigo mesmas a partir
                do processo de autoconhecimento. Neste processo nós cuidados de
                assuntos e/ou situações que causam sofrimento psíquico e podem
                levar ao adoecimento, criando ferramentas que ajudem a enfrentar
                as situações difíceis que encontramos no nosso cotidiano.
              </p>
            </div>
          </div>
        </div>
      </div>
      <hr />
      <div class="row">
        <div class="col-xl-3 col-lg-3">
          <div class="cta-one__icon-single">
            <div class="cta-one__icon">
              <i class="piloz-networking color-2"></i>
            </div>
            <h3>
              Formação
            </h3>
          </div>
        </div>
        <div class="col-xl-9 col-lg-9">
          <div class="cat_one_content">
            <div class="cta-one__text">
              <ul>
                <li>
                  Mestrado em Psicologia Clínica Pontifícia Universidade
                  Católica de São Paulo <br />
                  Conclusão: Agosto 2024
                </li>
                <li>
                  Pós Graduação em Psicanálise Curso: Teoria e Prática
                  Psicanalítica: Constituição do Sujeito e Intervenções Enlace –
                  Cursos de Especialização em Psicoterapia Psicanalítica <br />
                  Conclusão: Junho de 2022
                </li>
                <li>
                  Graduação em Psicologia Pontifíca Universidade Católica de
                  Campinas – PUC <br />
                  Conclusão: 2019
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "CallToAction"
};
</script>

<style scoped>
hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}
</style>
