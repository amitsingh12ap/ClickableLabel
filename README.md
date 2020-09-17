# ClickableLabel

Just confirm the protocols and you are ready to use.
// ViewController: UIViewController,ClickableLableProtocol, ClickableLabelInfoProtocol
// create a label add class type Clickablelabel
@IBOutlet weak var tnc2: ClickableLabel!

self.fullText = "Facebook"
self.clickableText = "Facebook"
self.urlString = "url_to_redirect"
self.tnm.configureLable(with: self, withFont: UIFont.systemFont(ofSize: 12))
self.tnm.delegate = self
