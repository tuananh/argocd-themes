A collection of ArgoCD custom themes
------------------------------------

These themes are available as part of Akuity managed Argo-CD platform. I just look at the source and extract the custom CSS from there.

## Usage

- If you use Argo-CD helm chart, there's a styles option to inject custom styles.

- Copy the CSS of the theme you want and paste it there.

- And then, in `argocd-cm` configmap, add an entry for `ui.cssurl` like the [instruction here](https://argo-cd.readthedocs.io/en/stable/operator-manual/custom-styles/).

## Lavender theme

![](./images/lavender-preview-1.png)

## Redold theme

![](./images/redold-preview-1.png)

## Slack theme

![](./images/slack-preview-1.png)

## Navy theme

![](./images/navy-preview-1.png)

## Beachball theme

![](./images/beachball-preview-1.png)

## Asphalt theme

![](./images/asphalt-preview-1.png)

## Terra theme

![](./images/terra-preview-1.png)
