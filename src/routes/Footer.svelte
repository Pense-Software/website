<script>
    import { Footer, FooterCopyright, FooterLinkGroup, FooterLink, FooterBrand, FooterIcon } from 'flowbite-svelte';
    import { FacebookSolid, GithubSolid, DiscordSolid, TwitterSolid } from 'flowbite-svelte-icons';
    import logo from "$lib/images/pense-logo-zoom.png"
  </script>
  
  <Footer footerType="socialmedia">
    <div class="md:flex md:justify-between">
      <div class="mb-6 md:mb-0">
        <FooterBrand href="/" src={logo} alt="Pense Logo" name="Pense" />
      </div>
      <div class="grid grid-cols-3 gap-8 sm:gap-6 sm:grid-cols-4">
        <div>
            <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white">Contact</h2>
            <FooterLinkGroup>
              <FooterLink liClass="mb-4" href="/">contact@pense.dev</FooterLink>
            </FooterLinkGroup>
          </div>
          
        <div>
          <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white">Office</h2>
          <FooterLinkGroup>
            <FooterLink liClass="mb-4" href="/">1111B S Governors Ave</FooterLink>
            <FooterLink liClass="mb-4" href="/">Dover, DE 19904 US</FooterLink>
          </FooterLinkGroup>
        </div>
        <div>
          <h2 class="mb-6 text-sm font-semibold uppercase text-gray-900 dark:text-white">Follow us</h2>
          <FooterLinkGroup>
            <FooterLink liClass="mb-4" href="https://github.com/Pense-Software">GitHub</FooterLink>
            <FooterLink liClass="mb-4" href="/">Twitter</FooterLink>
          </FooterLinkGroup>
        </div>
        <div>
          <h2 class="mb-6 text-sm font-semibold uppercase text-gray-900 dark:text-white">Legal</h2>
          <FooterLinkGroup>
            <FooterLink liClass="mb-4" href="/">Privacy Policy</FooterLink>
            <FooterLink liClass="mb-4" href="/">Terms & Conditions</FooterLink>
          </FooterLinkGroup>
        </div>
      </div>
    </div>
    <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
    <div class="sm:flex sm:items-center sm:justify-between">
      <FooterCopyright href="/" by="Pense, LLC." />
      <div class="flex mt-4 space-x-6 sm:justify-center sm:mt-0">
        <FooterIcon href="https://github.com/Pense-Software">
            <GithubSolid class="w-4 h-4 text-gray-500 dark:text-gray-500 hover:text-gray-900 dark:hover:text-white" />
          </FooterIcon>  
        <FooterIcon href="/">
          <TwitterSolid class="w-4 h-4 text-gray-500 dark:text-gray-500 hover:text-gray-900 dark:hover:text-white" />
        </FooterIcon>
        </div>
    </div>
  </Footer>