<template>

    <div class="container-fluid box d-flex flex-column justify-content-center" id="portfolio-section">
        <div class="row w-100 m-auto">
            <div class="col-12">
                <div class="subtitle mb-1 mb-md-5 text-center text-lg-start animate__animated animate__slideInUp" id="portfolio-title-box">Projects</div>

            <div class="scrolling-container animate__animated animate__slideInUp">
                <div class="row p-3 gap-3">

                    <div class="col-3 card glass-card">
                        <img src="@/assets/images/cards/sebastiao.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Final project Codemaster</h5>
                            <p class="card-text">
                                A responsive website using PHP on the backend for the writer Sebastião Alves.
                                A project compiling all that I've learned during the course, with a friendly backoffice to allow the user to perform changes on the website without the need to access the database.
                            </p>
                            <a href="https://github.com/andre-vaz/projecto_codemaster/tree/master" target="_blank" class="btn btn-primary">View Code</a>
                        </div>
                    </div>

                    <div class="col-3 card glass-card">
                        <img src="@/assets/images/cards/calculator_js.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Simple calculator</h5>
                            <p class="card-text">
                                Explore the fundamentals of JavaScript with my simple yet effective calculator project. Designed solely with JavaScript, this project was instrumental in honing my programming skills, offering a hands-on learning experience in web development.
                            </p>
                            <a href="https://github.com/andre-vaz/calculadora_js" target="_blank" class="btn btn-primary">View Code</a>
                        </div>
                    </div>

                    <div class="col-3 card glass-card">
                        <img src="@/assets/images/cards/todolist.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Simple ToDo List</h5>
                            <p class="card-text">
                                A ToDo List application built using Vue.js Node.js. The frontend interface allows users to easily manage tasks, while the backend handles data storage and retrieval through RESTful API endpoints.
                            </p>
                            <a href="https://github.com/andre-vaz/todolist" target="_blank" class="btn btn-primary">View Code</a>
                        </div>
                    </div>

                    <div class="col-3 card glass-card">
                        <img src="@/assets/images/cards/userlist.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Vue.js User List</h5>
                            <p class="card-text">
                                A sleek web app powered by Vue.js and Axios, showcasing a list of users fetched from JSONPlaceholder API. Users can seamlessly browse through user data including names, emails, companies, websites, and locations.
                            </p>
                            <a href="https://github.com/andre-vaz/vue_userlist" target="_blank" class="btn btn-primary">View Code</a>
                        </div>
                    </div>

                    <div class="col-3 card glass-card">
                        <img src="@/assets/images/cards/googlepage.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Google Landing Page</h5>
                            <p class="card-text">
                                An exercise done during my course, using only HTML and CSS.
                                Through crafting a dynamic landing page inspired by Google, I honed crucial skills in precise positioning and leveraged the flexibility of display flex.
                            </p>
                            <a href="https://github.com/andre-vaz/vue_userlist" target="_blank" class="btn btn-primary">View Code</a>
                        </div>
                    </div>

                </div>
            </div>
            </div>
        </div>
    </div>


</template>

<script>
    export default{
        name: "PortfolioPage",
        components: {

        },
    };
</script>