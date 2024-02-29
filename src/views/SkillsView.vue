<template>
    <div class="container-fluid box d-flex flex-column justify-content-center" id="skills-section">
        <div class="row d-flex justify-content-start align-items-center w-100">
            <div class="col-12 col-md-10 mx-auto">
                <div class="subtitle mb-5 text-center text-lg-start animate__animated animate__slideInUp" id="skills-title-box">Skills</div>
                <div class="row skills-container d-flex justify-content-start gap-md-5">
                    <div class="col-12 col-md-6 skills-box animate__animated animate__slideInUp" id="frontend-box">
                        <div class="skills-title mb-3">Front-End</div>
                        <div class="skills-img d-flex flex-wrap gap-3">
                            <img src="../assets/images/html5-wordmark.svg" alt="HTML">
                            <img src="../assets/images/css3-wordmark.svg" alt="CSS">
                            <img src="../assets/images/bootstrap-wordmark.svg" alt="Bootstrap">
                            <img src="../assets/images/javascript.svg" alt="javascript">
                            <img src="../assets/images/vue-logo.png" alt="javascript">
                        </div>
                    </div>
                    <div class="col-12 col-md-6 skills-box mt-3 mt-md-0 animate__animated animate__slideInUp" id="backend-box">
                        <div class="skills-title mb-3">Back-End</div>
                        <div class="skills-img d-flex flex-wrap gap-3">
                            <img src="../assets/images/java-wordmark.svg" alt="Java">
                            <img src="../assets/images/php.svg" alt="PHP">
                            <img src="../assets/images/sql-icon.png" alt="SQL">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default{
        name: "SkillsPage",
        components: {

        },
    };
</script>