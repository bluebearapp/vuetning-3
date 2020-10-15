<template>
    <div class="slds-form-element">
        <div class="slds-form-element__control">
            <div class="slds-rich-text-editor slds-grid slds-grid_vertical slds-nowrap">
                <div role="toolbar" class="slds-rich-text-editor__toolbar slds-shrink-none">
                    <ul aria-label="Format text" class="slds-button-group-list">
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="0">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#bold"></use>
                                </svg>
                                <span class="slds-assistive-text">Bold</span>
                            </button>
                        </li>
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#italic"></use>
                                </svg>
                                <span class="slds-assistive-text">Italic</span>
                            </button>
                        </li>
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#underline"></use>
                                </svg>
                                <span class="slds-assistive-text">Underline</span>
                            </button>
                        </li>
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#strikethrough"></use>
                                </svg>
                                <span class="slds-assistive-text">Strike Through</span>
                            </button>
                        </li>
                    </ul>
                    <ul aria-label="Format body" class="slds-button-group-list">
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#richtextbulletedlist"></use>
                                </svg>
                                <span class="slds-assistive-text">Bulleted List</span>
                            </button>
                        </li>
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#richtextnumberedlist"></use>
                                </svg>
                                <span class="slds-assistive-text">Numbered List</span>
                            </button>
                        </li>
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#richtextindent"></use>
                                </svg>
                                <span class="slds-assistive-text">Indent</span>
                            </button>
                        </li>
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#richtextoutdent"></use>
                                </svg>
                                <span class="slds-assistive-text">Outdent</span>
                            </button>
                        </li>
                    </ul>
                    <ul aria-label="Remove Formatting" class="slds-button-group-list">
                        <li>
                            <button class="slds-button slds-button_icon slds-button_icon-border-filled" tabindex="-1">
                                <svg class="slds-button__icon" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#remove_formatting"></use>
                                </svg>
                                <span class="slds-assistive-text">Remove Formatting</span>
                            </button>
                        </li>
                    </ul>
                </div>
                <div class="slds-rich-text-editor__textarea slds-grid">
                    <div aria-label="Compose text" contenteditable="true" class="slds-rich-text-area__content slds-text-color_weak slds-grow">
                        Compose text...
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "SldsRichTextEditor"
}
</script>

<style scoped>

</style>
