<style scoped>
h1{
    display: inline-block !important;
    font-weight: 900;
    color: blue;
}
h3{
    padding: 0 24px;
}
.row,.col{
    padding: 0;
    margin: 0;
}
label{
    font-weight: 500;
}
select,input{
    background-color: #e7e7e7;
    margin-bottom: 1rem;
}
input:hover,input:focus,select:hover,select:focus{
    -webkit-appearance:none;
    box-shadow: none !important;
}
.main{
    background-color: #f8f8f8;
    border-radius: 8px;
    margin-top: 2rem;
}
.ack{
    float: right;
}
button{
    margin: 0 0.3rem;
}
</style>

<template>
<div class="main container">
    <div class="p-2">
        <h1 class="m-2">Store <span style="font-weight:100;color:black">Management</span></h1>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-md-6 col-lg-6 col-sm-12 col-xs-12">
                <div class="mb-2">
                    <label for="exampleInputEmail1" class="form-label mb-0">Employee Name:</label>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>
            </div>
            <div class="col-md-6 col-lg-6 col-sm-12 col-xs-12">
                <div class="mb-2">
                    <label for="exampleInputEmail1" class="form-label mb-0">Employee ID:</label>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>
            </div>
        </div>
    </div>
    <h3>Acknowledgment</h3>
    <div class="container p-4">
        <table class="table text-center">
            <thead>
                <tr class="table-dark">
                    <th scope="col">ID</th>
                    <th scope="col">Name</th>
                    <th scope="col">Date</th>
                    <th scope="col">Requested item</th>
                    <th scope="col">Unit</th>
                    <th scope="col">Action</th>
                </tr>
            </thead>
            <tbody class="table-secondary">
                <tr>
                    <th scope="row">1</th>
                    <td>Mark</td>
                    <td>12/02/2021</td>
                    <td>Pen</td>
                    <td>5</td>
                    <td>
                        <button class="btn btn-success">Approve</button>
                        <button class="btn btn-danger ">Danger</button>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</div>
</template>

<script>
export default ({
   name:'Acknowledgment'
})
</script>
