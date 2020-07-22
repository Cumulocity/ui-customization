# Example Cumulocity IoT UI customization

To deploy:

* zip the app you want to deploy, say ui-assets:

      cd ui-assets
      jar -cvfM ui-assets.zip *json *html *svg *ico *css

* deploy it to cumulocity, either by uploading the zip through the UI, or by issuing:

       c8ycli deploy -u https://<your_tenant>.cumulocity.com  ui-assets.zip
