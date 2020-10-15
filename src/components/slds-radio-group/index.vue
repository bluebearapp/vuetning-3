<template>
    <fieldset class="slds-form-element">
        <legend class="slds-form-element__legend slds-form-element__label">Radio Group Label</legend>
        <div class="slds-form-element__control">
            <span class="slds-radio">
                <input type="radio" id="radio-5" value="radio-5" name="default" checked="" />
                <label class="slds-radio__label" for="radio-5">
                    <span class="slds-radio_faux"></span>
                    <span class="slds-form-element__label">Radio Label One</span>
                </label>
            </span>
            <span class="slds-radio">
                <input type="radio" id="radio-6" value="radio-6" name="default" />
                <label class="slds-radio__label" for="radio-6">
                    <span class="slds-radio_faux"></span>
                    <span class="slds-form-element__label">Radio Label Two</span>
                </label>
            </span>
        </div>
    </fieldset>
</template>

<script>
export default {
    name: "SldsRadioGroup"
}
</script>

<style scoped>

</style>
