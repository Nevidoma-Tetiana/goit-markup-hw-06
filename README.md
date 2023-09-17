<div class="backdrop is-hidden" data-modal>
            <div class="modal">
                <button class="modal__btn" type="button" data-modal-close>
                    <svg class="modal-close-icon" width="18" height="18">
                        <use href="./image/icon/symbol-defs.svg#close-icon"></use>
                    </svg>
                </button>
                <p class="modal__title">Залиште свої дані, ми вам передзвонимо</p>
                <form>
                    <div class="modal__field">
                        <label class="modal__label" for="user-name">Имя</label>
                        <input type="text" class="modal__input" name="user-name" id="user-name" />
                        <svg class="modal__icon" width="18" height="18">
                            <use href="./image/icon/symbol-defs.svg#icon-person-black"></use>
                        </svg>
                    </div>

                    <div class="modal__field">
                        <label class="modal__label" for="user-number">Телефон</label>
                        <input
                            type="tel"
                            class="modal__input"
                            name="user-number"
                            id="user-number"
                        />
                        <svg class="modal__icon" width="18" height="18">
                            <use href="./image/icon/symbol-defs.svg#icon-phone-black"></use>
                        </svg>
                    </div>
                    <div class="modal__field">
                        <label class="modal__label" for="user-email">Пошта</label>
                        <input
                            type="email"
                            class="modal__input"
                            name="user-email"
                            id="user-email"
                        />
                        <svg class="modal__icon" width="18" height="18">
                            <use href="./image/icon/symbol-defs.svg#icon-email-black"></use>
                        </svg>
                    </div>
                    <div class="modal-textarea">
                        <label class="modal__label" for="user-coment">Коментар</label>
                        <textarea
                            class="modal-textarea__text"
                            name="user-coment"
                            id="user-coment"
                            placeholder="Введите текст"
                        ></textarea>
                    </div>
                    <div class="conditions">
                        <input
                            type="checkbox"
                            class="checkbox__input visually-hidden"
                            name="checkbox"
                            id="checkbox"
                        />
                        <label for="checkbox" class="checkbox__text"
                            >Погоджуюся з розсилкою та приймаю &nbsp;
                            <a class="checkbox__link" href="#">Умови договору</a>
                        </label>
                    </div>
                    <button class="form__btn" type="submit">Відправити</button>
                </form>
            </div>
        </div>
