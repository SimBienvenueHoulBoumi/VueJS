<template>
    <div id="search">

        <div class="input-group mb-3">
                <div class="input-group-prepend">
                    <label class="input-group-text" for="inputGroupSelect01">Où</label>
                </div>
                <select class="custom-select" id="inputGroupSelect01">
                    <option value="Nantes">Nantes</option>
                    <option value="Paris">Paris</option>
                    <option value="Tours">Tours</option>
                </select>
        </div>
            

            <button type="button" class="btn btn-primary">Search</button> 

          
    </div>
</template>

<script>
import 'bootstrap'
import 'bootstrap/dist/css/bootstrap.min.css'
export default {
name: 'SearchWeather'
}
</script>

<style>
    #search{
        margin: auto;
        margin-top: -35px;
        width: 854px;
        height: 155px;
        padding: 2px;
        background-color: rgb(244, 242, 250);
    }
.input-group, .mb-3{
   margin-top: 15px;
   padding: 10px;
}
    
</style>