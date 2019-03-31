<template>
    <div>
        <!-- FOOTER SECTION -->
        <footer class="main-footer bg-dark">
            <div class="container">
                <div class="row">
                    <div class="col text-center py-4">
                        <h3>Accessful</h3>
                        <p>Copyright &copy; <span id="year"></span></p>
                        <button class="btn btn-primary" data-toggle="modal" data-target="#contactModal">Contact Us</button>
                    </div>
                </div>
            </div>
    
        </footer>
    
        <!-- CONTACT MODAL -->
        <div class="modal fade text-dark" id="contactModal">
            <div class="modal-dialog">
                <div class="modal-content">
    
                    <div class="modal-header">
                        <h5 class="modal-title">Contact Us</h5>
                        <button class="close" data-dismiss="modal"><span>&times;</span></button>
                    </div>
    
                    <div class="modal-body">
                        <form>
                            <div class="form-group">
                                <label for="name">Name</label>
                                <input type="text" class="form-control">
                            </div>
                            <div class="form-group">
                                <label for="email">Email</label>
                                <input type="email" class="form-control">
                            </div>
                            <div class="form-group">
                                <label for="Message">Message</label>
                                <input type="text" class="form-control">
                            </div>
                        </form>
                    </div>
    
                    <div class="modal-footer">
                        <button class="btn btn-primary btn-block">Submit</button>
                    </div>
    
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'footerSection'
    };
</script>

<style scoped>
    
</style>