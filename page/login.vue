<template>
    <section class="section is-relative">
        <div class="mb-10 is-flex is-hidden-widescreen">
            <img
                class="image is-fullwidth"
                style="width: 160px"
                src="@/assets/cronos-assets/elements/left-top.svg"
                alt=""
            />
        </div>
        <img
            class="is-absolute is-block-desktop is-hidden-touch is-top-0 is-left-0 image"
            src="@/assets/cronos-assets/elements/left-top.svg"
            alt=""
        />
        <img
            class="is-absolute is-block-desktop is-hidden-touch is-top-0 is-right-0 image"
            src="@/assets/cronos-assets/elements/right-top.svg"
            alt=""
        />
        <img
            class="is-absolute is-block-desktop is-hidden-touch is-bottom-0 is-left-0 image"
            src="@/assets/cronos-assets/elements/left-bottom.svg"
            alt=""
        />
        <img
            class="is-absolute is-block-desktop is-hidden-touch is-bottom-0 is-right-0 image"
            src="@/assets/cronos-assets/elements/right-bottom.svg"
            alt=""
        />
        <div class="container">
            <div class="has-mw-md mx-auto has-text-centered">
                <div class="has-text-centered">
                    <form action="#">
                        <span class="tag is-warning is-light is-uppercase"
                            >Sign Up</span
                        >
                        <h3 class="mt-6 mb-8 title is-size-3 is-spaced">
                            Create new account
                        </h3>
                        <div class="control mb-6">
                            <input
                                class="input"
                                type="email"
                                placeholder="E-mail address"
                            />
                        </div>
                        <div class="control mb-6">
                            <input
                                class="input"
                                type="password"
                                placeholder="Password"
                            />
                        </div>
                        <div class="control mb-6">
                            <input
                                class="input"
                                type="password"
                                placeholder="Repeat password"
                            />
                        </div>
                        <label class="checkbox mb-5">
                            <input
                                class="mr-4"
                                type="checkbox"
                                name="terms"
                                value="1"
                            />
                            <small class="has-text-grey-dark"
                                >Bằng cách đăng ký, là bạn đã chấp thuận với
                                chúng tôi về
                                <a
                                    class="has-text-grey-dark has-text-weight-bold"
                                    href="#"
                                    >Terms, Data Policy</a
                                >
                                and
                                <a
                                    class="has-text-grey-dark has-text-weight-bold"
                                    href="#"
                                    >Cookies Policy</a
                                >.</small
                            >
                        </label>
                        <button class="button is-warning is-fullwidth">
                            Đăng ký tài khoản
                        </button>
                    </form>
                </div>
            </div>
        </div>
        <div class="mt-10 is-flex is-hidden-widescreen">
            <img
                class="ml-auto image is-fullwidth"
                style="width: 160px"
                src="@/assets/cronos-assets/elements/right-bottom.svg"
                alt=""
            />
        </div>
    </section>
</template>
