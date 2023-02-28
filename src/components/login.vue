<template>
    <Modal>
      <ModalForm :title="Login" :excerpt="Welcome back again!">
        <template #form>
            <form>
                <input type="email" name="" v-model="email" id="">
                <input type="password" v-model="password" />
                <button>Submit</button>
            </form>
        </template>

      </ModalForm>
    </Modal>
    
    

</template>
<script>
    import ModalForm from './ModalForm.vue';
    import Modal from './Modal.vue';
    export default {
        components: {
            ModalForm,
            Modal
        },
        data() {
            return {
                email: "",
                password: "",
            }
        }
    }

</script>