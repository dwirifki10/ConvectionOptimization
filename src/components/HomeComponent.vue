<script setup>
</script>
<template>
    <div class="container p-50">
        <div class="accordion" id="accordionExample">
            <div class="accordion-item mb-3">
                <h2 class="accordion-header">
                <button class="accordion-button btn btn-primary fw-bold" data-bs-toggle="collapse"  data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne" type="button">
                    WHAT IS GARMENTPLANX ?
                </button>
                </h2>
                <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <div class="border p-3">
                            <strong>GARMENTPLANX is aplication for Production Planning in the Garment Industry Using Simplex Method.</strong>
                            <br><br>
                            <strong>GARMENTPLANX</strong> is a cutting-edge software application designed specifically for production planning in the garment industry. Its primary function is to determine the optimal quantities of various product types in a garment manufacturing business using the powerful simplex method. This application streamlines the production process, allowing manufacturers to efficiently meet customer demands while optimizing resource allocation and minimizing costs. <br><br>

                            <strong>Background:</strong>
                            In the fast-paced and highly competitive garment industry, efficient production planning is crucial for success. Traditional manual methods of production planning are often time-consuming, error-prone, and may not yield the most optimal results. GARMENTPLANX addresses these challenges by employing the simplex method, a mathematical optimization technique, to find the best production plan given certain constraints and objectives. <br><br>

                            <strong>Features and Functionality:</strong>
                            GARMENTPLANX boasts a wide array of features and functionalities that make it a valuable tool for garment manufacturers. Some of its key features include:<br><br>

                            a. User-friendly Interface: The application provides an intuitive and user-friendly interface that allows manufacturers to input relevant data easily. Users can specify the available resources, production capacities, and customer demand for each product type.<br><br>

                            b. Simplex Method: GARMENTPLANX utilizes the simplex method, a linear programming algorithm, to optimize the production plan. This method efficiently calculates the optimal quantities of each product type that should be manufactured to maximize profits or minimize costs, taking into account the constraints imposed by available resources.
                        </div> 
                    </div>
                </div>
            </div>
            <div class="accordion-item mb-3">
                <h2 class="accordion-header">
                <button class="accordion-button btn btn-primary fw-bold" data-bs-toggle="collapse"  data-bs-target="#collapseTwo" aria-expanded="true" aria-controls="collapseTwo" type="button">
                   HOW TO USE IT ?
                </button>
                </h2>
                <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <div class="border text-center p-3">
                            <strong>Stay Tuned !!! For Documentation.</strong>
                        </div> 
                    </div>
                </div>
            </div>
            <div class="accordion-item mb-3">
                <h2 class="accordion-header">
                <button class="accordion-button btn btn-primary fw-bold" data-bs-toggle="collapse"  data-bs-target="#collapseThree" aria-expanded="true" aria-controls="collapseThree" type="button">
                    WHAT ABOUT MY PRIVACY AND DATA ?
                </button>
                </h2>
                <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <div class="border p-3" style="height: 180px;">
                            You need not worry about your privacy and data. Your data will be stored locally in LocalStorage. The data stored in LocalStorage will be encrypted by the system, ensuring that you have no need for concern. We take data security seriously and have implemented robust encryption measures to protect your information from unauthorized access. Rest assured, your personal data will remain confidential and treated with the utmost care in accordance with our strict privacy policies
                        </div> 
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .p-50{
        padding-top: 10%;
    }
    .accordion-button:not(.collapse) {
        background-color: #FFFFFF;
        box-shadow: none;
        color: #FFFFFF;
    }
    .border {
        border-radius: 15px;
        overflow-y: auto;
        height: 250px;
    }
</style>